<template>
  <div id="board">
    <div class="outer_board">
      <table class="board">
        <tr>
          <td class="white" rowspan="3" data-name="zero" @click="setChip">
            <div>0</div>
            <Chip :value="zero" />
          </td>
          <td class="white" data-name="three" bgcolor="DC143C" @click="setChip">
            <div>3</div>
            <Chip :value="three" />
          </td>
          <td class="white" data-name="six" bgcolor="black" @click="setChip">
            <div>6</div>
            <Chip :value="six" />
          </td>
          <td class="white" data-name="nine" bgcolor="DC143C" @click="setChip">
            <div>9</div>
            <Chip :value="nine" />
          </td>
          <td class="white" data-name="twelve" bgcolor="DC143C" @click="setChip">
            <div>12</div>
            <Chip :value="twelve" />
          </td>
          <td class="white" data-name="fifteen" bgcolor="black" @click="setChip">
            <div>15</div>
            <Chip :value="fifteen" />
          </td>
          <td class="white" data-name="eighteen" bgcolor="DC143C" @click="setChip">
            <div>18</div>
            <Chip :value="eighteen" />
          </td>
          <td class="white" data-name="twentyone" bgcolor="DC143C" @click="setChip">
            <div>21</div>
            <Chip :value="twentyone" />
          </td>
          <td class="white" data-name="twentyfour" bgcolor="black" @click="setChip">
            <div>24</div>
            <Chip :value="twentyfour" />
          </td>
          <td class="white" data-name="twentyseven" bgcolor="DC143C" @click="setChip">
            <div>27</div>
            <Chip :value="twentyseven" />
          </td>
          <td class="white" data-name="thirty" bgcolor="DC143C" @click="setChip">
            <div>30</div>
            <Chip :value="thirty" />
          </td>
          <td class="white" data-name="thirtythree" bgcolor="black" @click="setChip">
            <div>33</div>
            <Chip :value="thirtythree" />
          </td>
          <td class="white" data-name="thirtysix" bgcolor="DC143C" @click="setChip">
            <div>36</div>
            <Chip :value="thirtysix" />
          </td>
          <td class="white" data-name="lineOne" @click="setChip">
            <div>&rarr;</div>
            <Chip :value="lineOne" />
          </td>
        </tr>
        <tr>
          <td class="white" data-name="two" bgcolor="black" @click="setChip">
            <div>2</div>
            <Chip :value="two" />
          </td>
          <td class="white" data-name="five" bgcolor="DC143C" @click="setChip">
            <div>5</div>
            <Chip :value="five" />
          </td>
          <td class="white" data-name="eight" bgcolor="black" @click="setChip">
            <div>8</div>
            <Chip :value="eight" />
          </td>
          <td class="white" data-name="eleven" bgcolor="black" @click="setChip">
            <div>11</div>
            <Chip :value="eleven" />
          </td>
          <td class="white" data-name="fourteen" bgcolor="DC143C" @click="setChip">
            <div>14</div>
            <Chip :value="fourteen" />
          </td>
          <td class="white" data-name="seventeen" bgcolor="black" @click="setChip">
            <div>17</div>
            <Chip :value="seventeen" />
          </td>
          <td class="white" data-name="twenty" bgcolor="black" @click="setChip">
            <div>20</div>
            <Chip :value="twenty" />
          </td>
          <td class="white" data-name="twentythree" bgcolor="DC143C" @click="setChip">
            <div>23</div>
            <Chip :value="twentythree" />
          </td>
          <td class="white" data-name="twentysix" bgcolor="black" @click="setChip">
            <div>26</div>
            <Chip :value="twentysix" />
          </td>
          <td class="white" data-name="twentynine" bgcolor="black" @click="setChip">
            <div>29</div>
            <Chip :value="twentynine" />
          </td>
          <td class="white" data-name="thirtytwo" bgcolor="DC143C" @click="setChip">
            <div>32</div>
            <Chip :value="thirtytwo" />
          </td>
          <td class="white" data-name="thirtyfive" bgcolor="black" @click="setChip">
            <div>35</div>
            <Chip :value="thirtyfive" />
          </td>
          <td class="white" data-name="lineTwo" @click="setChip">
            &rarr;
            <Chip :value="lineTwo" />
          </td>
        </tr>
        <tr>
          <td class="white" data-name="one" bgcolor="DC143C" @click="setChip">
            <div>1</div>
            <Chip :value="one" />
          </td>
          <td class="white" data-name="four" bgcolor="black" @click="setChip">
            <div>4</div>
            <Chip :value="four" />
          </td>
          <td class="white" data-name="seven" bgcolor="DC143C" @click="setChip">
            <div>7</div>
            <Chip :value="seven" />
          </td>
          <td class="white" data-name="ten" bgcolor="black" @click="setChip">
            <div>10</div>
            <Chip :value="ten" />
          </td>
          <td class="white" data-name="thirteen" bgcolor="black" @click="setChip">
            <div>13</div>
            <Chip :value="thirteen" />
          </td>
          <td class="white" data-name="sixteen" bgcolor="DC143C" @click="setChip">
            <div>16</div>
            <Chip :value="sixteen" />
          </td>
          <td class="white" data-name="nineteen" bgcolor="DC143C" @click="setChip">
            <div>19</div>
            <Chip :value="nineteen" />
          </td>
          <td class="white" data-name="twentytwo" bgcolor="black" @click="setChip">
            <div>22</div>
            <Chip :value="twentytwo" />
          </td>
          <td class="white" data-name="twentyfive" bgcolor="DC143C" @click="setChip">
            <div>25</div>
            <Chip :value="twentyfive" />
          </td>
          <td class="white" data-name="twentyeight" bgcolor="black" @click="setChip">
            <div>28</div>
            <Chip :value="twentyeight" />
          </td>
          <td class="white" data-name="thirtyone" bgcolor="black" @click="setChip">
            <div>31</div>
            <Chip :value="thirtyone" />
          </td>
          <td class="white" data-name="thirtyfour" bgcolor="DC143C" @click="setChip">
            <div>34</div>
            <Chip :value="thirtyfour" />
          </td>
          <td class="normal" data-name="lineThree" @click="setChip">
            &rarr;
            <Chip :value="lineThree" />
          </td>
        </tr>
        <tr>
          <td class="nothing"></td>
          <td class="normal" colspan="4" data-name="oneToTwelve" @click="setChip">
            <div>1st 12</div>
            <Chip :value="oneToTwelve" />
          </td>
          <td class="normal" colspan="4" data-name="thirteenToTwentyfour" @click="setChip">
            <div>2nd 12</div>
            <Chip :value="thirteenToTwentyfour" />
          </td>
          <td class="normal" colspan="4" data-name="twentyfiveToThirtysix" @click="setChip">
            <div>3rd 12</div>
            <Chip :value="twentyfiveToThirtysix" />
          </td>
        </tr>
        <tr>
          <td class="nothing"></td>
          <td class="normal" colspan="2" data-name="even" @click="setChip">
            <div>EVEN</div>
            <Chip :value="even" />
          </td>
          <td class="normal" colspan="2" data-name="oneToEighteen" @click="setChip">
            <div>1 - 18</div>
            <Chip :value="oneToEighteen" />
          </td>
          <td class="normal black" colspan="2" data-name="black" @click="setChip">
            <div>Black</div>
            <Chip :value="black" />
          </td>
          <td class="normal red" colspan="2" data-name="red" @click="setChip">
            <div>Red</div>
            <Chip :value="red" />
          </td>
          <td class="normal" colspan="2" data-name="nineteenToThirtysix" @click="setChip">
            <div>19 - 36</div>
            <Chip :value="nineteenToThirtysix" />
          </td>
          <td class="normal" colspan="2" data-name="odd" @click="setChip">
            <div>ODD</div>
            <Chip :value="odd" />
          </td>
        </tr>
      </table>
    </div>
    <div>
        <p>Bilanci: <b>{{ currentBalance }} EUR</b>
        {{ lastWin == 0 ? "" : " (+ " + lastWin + " EUR)" }}</p>
        <button @click="clearBoard">Pastro tabelën</button>&nbsp;
        <button @click="resetGame">Reseto lojën</button>
      </div>
  </div>
</template>

<script>
import { GameStore, GameStoreChanger } from "../services/store.js";
import Chip from "../components/Chip";

export default {
  name: "Board",
  data() {
    return {
      //When placed on just one full number
      zero: 0,
      one: 0,
      two: 0,
      three: 0,
      four: 0,
      five: 0,
      six: 0,
      seven: 0,
      eight: 0,
      nine: 0,
      ten: 0,
      eleven: 0,
      twelve: 0,
      thirteen: 0,
      fourteen: 0,
      fifteen: 0,
      sixteen: 0,
      seventeen: 0,
      eighteen: 0,
      nineteen: 0,
      twenty: 0,
      twentyone: 0,
      twentytwo: 0,
      twentythree: 0,
      twentyfour: 0,
      twentyfive: 0,
      twentysix: 0,
      twentyseven: 0,
      twentyeight: 0,
      twentynine: 0,
      thirty: 0,
      thirtyone: 0,
      thirtytwo: 0,
      thirtythree: 0,
      thirtyfour: 0,
      thirtyfive: 0,
      thirtysix: 0,
      //Others
      black: 0, //Placed on black
      red: 0, //Placed on red
      even: 0, //Placed on pair
      odd: 0, //Placed on impair
      oneToEighteen: 0, //Placed 1 - 18
      nineteenToThirtysix: 0, //Placed 19 -36
      oneToTwelve: 0, //Placed 1 - 12
      thirteenToTwentyfour: 0, //Placed 13 - 24
      twentyfiveToThirtysix: 0, //Placed 25 - 36
      lineOne: 0,
      lineTwo: 0,
      lineThree: 0,
      lastWin: 0
    };
  },
  components: {
    Chip
  },
  computed: {
    currentNumber() {
      return GameStore.currentNumber;
    },
    currentBalance() {
      return GameStore.currentBalance;
    }
  },
  watch: {
    currentNumber(val) {
      this.evaluate(val);
      setTimeout(function() {
        this.sumUpBoard();
      }.bind(this), 2000);
    }
  },
  methods: {
    evaluate(val) {
      var color = val.color;
      var number = val.number;

      //Colors
      switch (color) {
        case "black":
          this.red = 0;
          this.black = this.black * 2;
          break;
        case "red":
          this.black = 0;
          this.red = this.red * 2;
          break;
        default:
          this.black = this.black / 2;
          this.red = this.red / 2;
      }

      //1 - 18 and 19 - 36
      if (number >= 1 && number <= 18) {
        this.nineteenToThirtysix = 0;
        this.oneToEighteen = this.oneToEighteen * 2;
      } else if (number >= 19 && number <= 36) {
        this.oneToEighteen = 0;
        this.nineteenToThirtysix = this.nineteenToThirtysix * 2;
      } else {
        this.oneToEighteen = 0;
        this.nineteenToThirtysix = 0;
      }

      //Odd and even
      if (number != 0 && number % 2 == 0) {
        //Pair
        this.odd = 0;
        this.even = this.even * 2;
      } else if (number != 0 && number % 2 == 1) {
        //Odd
        this.even = 0;
        this.odd = this.odd * 2;
      } else {
        this.even = this.even / 2;
        this.odd = this.odd / 2;
      }

      //1 - 12 / 13 - 24 / 25 - 36
      if (number >= 1 && number <= 12) {
        this.thirteenToTwentyfour = 0;
        this.twentyfiveToThirtysix = 0;
        this.oneToTwelve = this.oneToTwelve * 3;
      } else if (number >= 13 && number <= 24) {
        this.oneToTwelve = 0;
        this.twentyfiveToThirtysix = 0;
        this.thirteenToTwentyfour = this.thirteenToTwentyfour * 3;
      } else if (number >= 25 && number <= 36) {
        this.oneToTwelve = 0;
        this.thirteenToTwentyfour = 0;
        this.twentyfiveToThirtysix = this.twentyfiveToThirtysix * 3;
      } else {
        this.oneToTwelve = 0;
        this.thirteenToTwentyfour = 0;
        this.twentyfiveToThirtysix = 0;
      }

      //Lines
      if (number != 0 && number % 3 == 0) {
        //Line of 36 - 3
        this.lineOne = 0;
        this.lineTwo = 0;
        this.lineThree = this.lineThree * 3;
      } else if (number != 0 && number % 3 == 1) {
        //Line of 34 - 1
        this.lineThree = 0;
        this.lineTwo = 0;
        this.lineOne = this.lineOne * 3;
      } else if (number != 0 && number % 3 == 2) {
        //Line of 35 - 2
        this.lineOne = 0;
        this.lineThree = 0;
        this.lineTwo = this.lineTwo * 3;
      } else {
        this.lineOne = 0;
        this.lineThree = 0;
        this.lineTwo = 0;
      }

      //Evaluate full numbers
      var temp_value = 0;
      switch (number) {
        case 0:
          temp_value = this.zero;
          this.resetNaturalNumbers();
          this.zero = temp_value * 36;
          break;
        case 1:
          temp_value = this.one;
          this.resetNaturalNumbers();
          this.one = temp_value * 36;
          break;
        case 2:
          temp_value = this.two;
          this.resetNaturalNumbers();
          this.two = temp_value * 36;
          break;
        case 3:
          temp_value = this.three;
          this.resetNaturalNumbers();
          this.three = temp_value * 36;
          break;
        case 4:
          temp_value = this.four;
          this.resetNaturalNumbers();
          this.four = temp_value * 36;
          break;
        case 5:
          temp_value = this.five;
          this.resetNaturalNumbers();
          this.five = temp_value * 36;
          break;
        case 6:
          temp_value = this.six;
          this.resetNaturalNumbers();
          this.six = temp_value * 36;
          break;
        case 7:
          temp_value = this.seven;
          this.resetNaturalNumbers();
          this.seven = temp_value * 36;
          break;
        case 8:
          temp_value = this.eight;
          this.resetNaturalNumbers();
          this.eight = temp_value * 36;
          break;
        case 9:
          temp_value = this.nine;
          this.resetNaturalNumbers();
          this.nine = temp_value * 36;
          break;
        case 10:
          temp_value = this.ten;
          this.resetNaturalNumbers();
          this.ten = temp_value * 36;
          break;
        case 11:
          temp_value = this.eleven;
          this.resetNaturalNumbers();
          this.eleven = temp_value * 36;
          break;
        case 12:
          temp_value = this.twelve;
          this.resetNaturalNumbers();
          this.twelve = temp_value * 36;
          break;
        case 13:
          temp_value = this.thirteen;
          this.resetNaturalNumbers();
          this.thirteen = temp_value * 36;
          break;
        case 14:
          temp_value = this.fourteen;
          this.resetNaturalNumbers();
          this.fourteen = temp_value * 36;
          break;
        case 15:
          temp_value = this.fifteen;
          this.resetNaturalNumbers();
          this.fifteen = temp_value * 36;
          break;
        case 16:
          temp_value = this.sixteen;
          this.resetNaturalNumbers();
          this.sixteen = temp_value * 36;
          break;
        case 17:
          temp_value = this.seventeen;
          this.resetNaturalNumbers();
          this.seventeen = temp_value * 36;
          break;
        case 18:
          temp_value = this.eighteen;
          this.resetNaturalNumbers();
          this.eighteen = temp_value * 36;
          break;
        case 19:
          temp_value = this.nineteen;
          this.resetNaturalNumbers();
          this.nineteen = temp_value * 36;
          break;
        case 20:
          temp_value = this.twenty;
          this.resetNaturalNumbers();
          this.twenty = temp_value * 36;
          break;
        case 21:
          temp_value = this.twentyone;
          this.resetNaturalNumbers();
          this.twentytwo = temp_value * 36;
          break;
        case 22:
          temp_value = this.twentytwo;
          this.resetNaturalNumbers();
          this.twentytwo = temp_value * 36;
          break;
        case 23:
          temp_value = this.twentythree;
          this.resetNaturalNumbers();
          this.twentythree = temp_value * 36;
          break;
        case 24:
          temp_value = this.twentyfour;
          this.resetNaturalNumbers();
          this.twentyfour = temp_value * 36;
          break;
        case 25:
          temp_value = this.twentyfive;
          this.resetNaturalNumbers();
          this.twentyfive = temp_value * 36;
          break;
        case 26:
          temp_value = this.twentysix;
          this.resetNaturalNumbers();
          this.twentysix = temp_value * 36;
          break;
        case 27:
          temp_value = this.twentyseven;
          this.resetNaturalNumbers();
          this.twentyseven = temp_value * 36;
          break;
        case 28:
          temp_value = this.twentyeight;
          this.resetNaturalNumbers();
          this.twentyeight = temp_value * 36;
          break;
        case 29:
          temp_value = this.twentynine;
          this.resetNaturalNumbers();
          this.twentynine = temp_value * 36;
          break;
        case 30:
          temp_value = this.thirty;
          this.resetNaturalNumbers();
          this.thirty = temp_value * 36;
          break;
        case 31:
          temp_value = this.thirtyone;
          this.resetNaturalNumbers();
          this.thirtyone = temp_value * 36;
          break;
        case 32:
          temp_value = this.thirtytwo;
          this.resetNaturalNumbers();
          this.thirtytwo = temp_value * 36;
          break;
        case 33:
          temp_value = this.thirtythree;
          this.resetNaturalNumbers();
          this.thirtythree = temp_value * 36;
          break;
        case 34:
          temp_value = this.thirtyfour;
          this.resetNaturalNumbers();
          this.thirtyfour = temp_value * 36;
          break;
        case 35:
          temp_value = this.thirtyfive;
          this.resetNaturalNumbers();
          this.thirtyfive = temp_value * 36;
          break;
        case 36:
          temp_value = this.thirtysix;
          this.resetNaturalNumbers();
          this.thirtysix = temp_value * 36;
          break;
        default:
          this.resetNaturalNumbers();
          break;
      }
    },
    resetNaturalNumbers() {
      this.zero = 0;
      this.one = 0;
      this.two = 0;
      this.three = 0;
      this.four = 0;
      this.five = 0;
      this.six = 0;
      this.seven = 0;
      this.eight = 0;
      this.nine = 0;
      this.ten = 0;
      this.eleven = 0;
      this.twelve = 0;
      this.thirteen = 0;
      this.fourteen = 0;
      this.fifteen = 0;
      this.sixteen = 0;
      this.seventeen = 0;
      this.eighteen = 0;
      this.nineteen = 0;
      this.twenty = 0;
      this.twentyone = 0;
      this.twentytwo = 0;
      this.twentythree = 0;
      this.twentyfour = 0;
      this.twentyfive = 0;
      this.twentysix = 0;
      this.twentyseven = 0;
      this.twentyeight = 0;
      this.twentynine = 0;
      this.thirty = 0;
      this.thirtyone = 0;
      this.thirtytwo = 0;
      this.thirtythree = 0;
      this.thirtyfour = 0;
      this.thirtyfive = 0;
      this.thirtysix = 0;
    },
    setChip(e) {
      var element = e.target;
      if (element.nodeName === "DIV") {
        element = element.parentElement;
      }
      var type = element.getAttribute("data-name");

      if(this.currentBalance > 0) {
        this[type]++; //Increase the chip size
        GameStoreChanger.setNewBalance(this.currentBalance - 1);
      }
    },

    clearBoard() {
      this.resetNaturalNumbers();

      this.black = 0; //Placed on black
      this.red = 0; //Placed on red
      this.even = 0; //Placed on pair
      this.odd = 0; //Placed on impair
      this.oneToEighteen = 0; //Placed 1 - 18
      this.nineteenToThirtysix = 0; //Placed 19 -36
      this.oneToTwelve = 0; //Placed 1 - 12
      this.thirteenToTwentyfour = 0; //Placed 13 - 24
      this.twentyfiveToThirtysix = 0; //Placed 25 - 36
      this.lineOne = 0;
      this.lineTwo = 0;
      this.lineThree = 0;
    },
    resetGame() {
      GameStoreChanger.setNewBalance(50);
      this.clearBoard();
    }
  }
};
</script>

<style>
.outer_board {
  overflow-y: auto;
  width: 100%;
}

.board td {
  position: relative;
  border: white 1px solid;
  padding: 10px;
  font-weight: bold;
  text-transform: uppercase;
  cursor: pointer;
}

.board td.nothing {
  border: none;
  cursor: default;
}

/*.board td:not(.normal) {
  transform: rotate(90deg);
}*/

.board td > div {
  min-width: 20px;
}

.board {
  border-collapse: collapse;
  background-color: green;
  margin-left: auto;
  margin-right: auto;
}
.red {
  color: red;
}
.black {
  color: black;
}
.green {
  color: green;
}

  #diamond-img{
    width: 40px;
    height: 20px;
  }
</style>
