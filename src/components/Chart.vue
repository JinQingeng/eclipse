<template>
  <div id="card1">
    <div>
      <div id="card1_text">
        <p id="card1_title">统计图表</p>
      </div>
    </div>
    <div id="card1_content">
      <div class="line">
        <ve-line :data="chartData"></ve-line>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  data() {
    return {
      chartData: {
        columns: ["世纪", "日食", "偏食", "环食", "全食", "全环食"],
        rows: [
          {
            世纪: "0",
            日食: "248",
            偏食: "90",
            环食: "74",
            全食: "58",
            全环食: "25"
          },
          {
            世纪: "1",
            日食: "237",
            偏食: "80",
            环食: "75",
            全食: "63",
            全环食: "16"
          },
          {
            世纪: "2",
            日食: "227",
            偏食: "79",
            环食: "70",
            全食: "69",
            全环食: "5"
          },
          {
            世纪: "3",
            日食: "222",
            偏食: "73",
            环食: "74",
            全食: "65",
            全环食: "7"
          },
          {
            世纪: "4",
            日食: "233",
            偏食: "80",
            环食: "83",
            全食: "67",
            全环食: "2"
          },
          {
            世纪: "5",
            日食: "251",
            偏食: "93",
            环食: "86",
            全食: "65",
            全环食: "6"
          },
          {
            世纪: "6",
            日食: "251",
            偏食: "90",
            环食: "89",
            全食: "67",
            全环食: "4"
          },
          {
            世纪: "7",
            日食: "233",
            偏食: "77",
            环食: "86",
            全食: "66",
            全环食: "2"
          },
          {
            世纪: "8",
            日食: "222",
            偏食: "78",
            环食: "72",
            全食: "62",
            全环食: "6"
          },
          {
            世纪: "9",
            日食: "227",
            偏食: "76",
            环食: "83",
            全食: "65",
            全环食: "1"
          },
          {
            世纪: "10",
            日食: "241",
            偏食: "84",
            环食: "90",
            全食: "61",
            全环食: "6"
          },
          {
            世纪: "11",
            日食: "250",
            偏食: "92",
            环食: "82",
            全食: "61",
            全环食: "15"
          },
          {
            世纪: "12",
            日食: "246",
            偏食: "87",
            环食: "80",
            全食: "60",
            全环食: "18"
          },
          {
            世纪: "13",
            日食: "229",
            偏食: "76",
            环食: "72",
            全食: "54",
            全环食: "24"
          },
          {
            世纪: "14",
            日食: "222",
            偏食: "77",
            环食: "62",
            全食: "60",
            全环食: "19"
          },
          {
            世纪: "15",
            日食: "228",
            偏食: "75",
            环食: "69",
            全食: "62",
            全环食: "19"
          },
          {
            世纪: "16",
            日食: "248",
            偏食: "89",
            环食: "74",
            全食: "60",
            全环食: "24"
          },
          {
            世纪: "17",
            日食: "251",
            偏食: "92",
            环食: "78",
            全食: "62",
            全环食: "19"
          },
          {
            世纪: "18",
            日食: "242",
            偏食: "87",
            环食: "77",
            全食: "63",
            全环食: "15"
          },
          {
            世纪: "19",
            日食: "228",
            偏食: "78",
            环食: "71",
            全食: "68",
            全环食: "6"
          },
          {
            世纪: "20",
            日食: "224",
            偏食: "77",
            环食: "70",
            全食: "67",
            全环食: "7"
          },
          {
            世纪: "21",
            日食: "235",
            偏食: "79",
            环食: "82",
            全食: "65",
            全环食: "4"
          },
          {
            世纪: "22",
            日食: "248",
            偏食: "92",
            环食: "86",
            全食: "67",
            全环食: "3"
          },
          {
            世纪: "23",
            日食: "248",
            偏食: "88",
            环食: "86",
            全食: "66",
            全环食: "8"
          },
          {
            世纪: "24",
            日食: "237",
            偏食: "81",
            环食: "87",
            全食: "65",
            全环食: "1"
          },
          {
            世纪: "25",
            日食: "225",
            偏食: "83",
            环食: "71",
            全食: "63",
            全环食: "6"
          },
          {
            世纪: "26",
            日食: "227",
            偏食: "77",
            环食: "78",
            全食: "64",
            全环食: "5"
          },
          {
            世纪: "27",
            日食: "242",
            偏食: "84",
            环食: "92",
            全食: "63",
            全环食: "3"
          },
          {
            世纪: "28",
            日食: "254",
            偏食: "95",
            环食: "86",
            全食: "63",
            全环食: "9"
          },
          {
            世纪: "29",
            日食: "248",
            偏食: "91",
            环食: "80",
            全食: "64",
            全环食: "11"
          }
        ]
      }
    };
  }
};
</script>

<style lang="scss">
#card1 {
  border: 1px solid grey;
  position: absolute;
  padding: 2px;
  left: 15px;
  bottom: 81px;
  width: 25vw;
  height: 56vh;
  overflow: hidden;
}
#card1_text {
  width: 98.5%;
  height: 4vh;
  line-height: 24px;
  background: rgba(100, 191, 255, 0.3);
  padding-left: 2px;
  border-left: 2px solid #64bfff;
}
#card1_text p {
  font-size: 12px;
  color: #000;
  text-align: left;
  margin: 0;
}
#card1_content {
  height: 100%;
  width: 25vw;
  background-color: rgba(235, 245, 249, 0.6);
}
.line {
  width: 100%;
}
</style>
