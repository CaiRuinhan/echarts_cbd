<style scoped>
.box {
  width: 100%;
  height: 102vh;
  /* border: 1px solid red; */
  background: url("../../assets/cbd_icon/bg.png");
  background-size: 100% 100%;
}
.btn {
  width: 2.8vw;
  height: 2.6vw;
  position: absolute;
  top: 1.5vw;
  right: 1.5vw;
  cursor: pointer;
  border-radius: 50px;
  border: none;
  outline: none;
  font-weight: bold;
  font-size: 2vw;
  line-height: 1.8vw;
  background: rgb(194, 194, 194);
  opacity: 0;
  z-index: 1000;
}
.btn:hover {
  color: white;
  opacity: 1;
  z-index: 1000;
}
.btn1 {
  width: 3.5vw;
  height: 3.5vw;
  position: fixed;
  top: 1.7vw;
  right: 1.75vw;
  cursor: pointer;
  border-radius: 50px;
  border: none;
  outline: none;
  font-size: 2.3vw;
  line-height: 3.5vw;
  opacity: 0;
  font-weight: 1800;
  background: rgb(194, 194, 194);
  z-index: 1000;
}
.btn1:hover {
  color: white;
  opacity: 1;
  z-index: 1000;
}
.heads {
  width: 100%;
  height: 10.5vh;
  /* border: 1px solid red; */
}
.head_title_bg {
  width: 80%;
  height: 100%;
  padding-top: 1.1vh;
  margin: 0 auto;
  text-align: center;
  /* border: 1px solid white; */
  background: url("../../assets/cbd_icon/title_bg.png");
  background-size: 100% 100%;
}
.head_title1 {
  font-size: 1.8vw;
  margin-left: -5%;
  color: #61f1fe;
  font-weight: bold;
}
.head_title2 {
  font-size: 1.1vw;
  margin-left: -5%;
  color: #61f1fe;
  margin-top: -0.5vh;
}
.tab_left {
  width: 3%;
  height: 77vh;
  background: url("../../assets/images/tab_left.png");
  background-size: 100% 100%;
  position: absolute;
  left: 0;
  bottom: 5px;
  /* border: 1px solid; */
}
.tab_title {
  width: 100%;
  height: 33.3%;
  text-align: center;
  text-align-last: justify;
  writing-mode: vertical-rl;
  font-size: 20px;
  color: #02aee0;
  /* padding-right: 20%; */
  padding-top: 100%;
  padding-bottom: 100%;
  cursor: pointer;
  display: flex;
  /* border: 1px solid; */
}
.tab_titles {
  width: 100%;
  height: 33.3%;
  text-align: center;
  text-align-last: justify;
  writing-mode: vertical-rl;
  font-size: 20px;
  color: white;
  padding-top: 100%;
  padding-bottom: 100%;
  cursor: pointer;
  display: flex;
  /* border: 1px solid; */
}
.content {
  width: 94%;
  height: 91vh;
  margin-left: 4%;
  /* border: 1px solid; */
}
.content_top {
  width: 100%;
  height: 12vh;
  margin-top: 2vh;
  margin-bottom: 2vh;
  background: url("../../assets/cbd_icon/top_bg.png");
  background-size: 100% 100%;
  /* border: 1px solid; */
}
.content_top_top,
.content_top_bottom {
  width: 100%;
  height: 50%;
  display: flex;
  align-items: center;
  /* border: 1px solid; */
}
.content_content {
  width: 100%;
  height: 37vh;
  display: flex;
  margin-bottom: 2.5vh;
  /* border: 1px solid; */
}
.content_content_left,
.content_content_right {
  width: 49%;
  height: 100%;
  background: url("../../assets/cbd_icon/top_two_bg.png");
  background-size: 100% 100%;
  /* border: 1px solid; */
}
.content_content_left {
  margin-left: 0;
}
.content_content_right {
  margin-left: 2%;
}
.content_bottom {
  width: 100%;
  height: 33vh;
  background: url("../../assets/cbd_icon/bottom_bg.png");
  background-size: 100% 100%;
  padding-top: 0.1px;
  /* border: 1px solid; */
}
.all_car {
  width: 16%;
  height: 60%;
  margin-left: 2%;
  margin-top: 0.5%;
  background: url("../../assets/cbd_icon/input_bg.png");
  background-size: 100% 100%;
  border: none;
  padding-left: 0.5%;
  color: #17c6dd;
  font-size: 0.9vw;
}
.all_car2 {
  width: 16%;
  height: 60%;
  margin-left: 31vw;
  margin-top: 0.5%;
  background: url("../../assets/cbd_icon/input_bg.png");
  background-size: 100% 100%;
  border: none;
  padding-left: 0.5%;
  color: #17c6dd;
  font-size: 0.9vw;
}
.all_car1 {
  height: 10px;
  background: #13305a;
  border: none;
  font-size: 0.8vw;
  color: #aaeeff;
}
.search {
  width: 5%;
  height: 60%;
  margin-left: 1%;
  margin-top: 0.5%;
  /* margin-top: 1%; */
  background: url("../../assets/cbd_icon/input_bg.png");
  background-size: 100% 100%;
  color: white;
  font-size: 0.9vw;
  display: flex;
  justify-content: center;
  align-items: center;
  cursor: pointer;
}
.start_end_time {
  width: 30vw;
  height: 60%;
  margin-left: 2%;
  margin-bottom: 0.5%;
  background: url("../../assets/cbd_icon/long_bg.png");
  background-size: 100% 100%;
  display: flex;
  align-items: center;
  color: white;
  font-size: 0.8vw;
}
.start_end_time1 {
  width: 28vw;
  height: 60%;
  margin-left: 2%;
  margin-top: -11vh;
  background: url("../../assets/cbd_icon/long_bg.png");
  background-size: 100% 100%;
  display: flex;
  align-items: center;
  color: white;
  font-size: 0.8vw;
}
.content_top_bottom_text {
  width: 67%;
  height: 60%;
  margin-bottom: 0.5%;
  margin-left: 1vw;
  display: flex;
  align-items: center;
  color: #19ecff;
  font-size: 1vw;
  /* border: 1px solid; */
}
.content_top_bottom_text1 {
  width: 67%;
  height: 60%;
  margin-bottom: 0.5%;
  margin-left: -25vw;
  display: flex;
  align-items: center;
  color: #19ecff;
  font-size: 1vw;
  /* border: 1px solid; */
}
>>> .ivu-input {
  width: 110%;
  height: 3.6vh;
  font-size: 0.9vw;
  margin-left: -1vw;
  color: white;
  background: url("../../assets/cbd_icon/input_bg.png");
  background-size: 100% 100%;
  border: none;
}
>>> .ivu-picker-panel-body {
  background: #13305a;
}
>>> .ivu-radio-inner::after {
  background: #19daee;
}
.content_content_small_title {
  width: 10vw;
  height: 4vh;
  text-align: center;
  line-height: 4.2vh;
  font-size: 0.9vw;
  color: #eff3f5;
  margin: 0 auto;
  margin-top: 15px;
  background: url("../../assets/cbd_icon/small_bg.png");
  background-size: 100% 100%;
  /* border: 1px solid; */
}
.content_content_small_left {
  width: 100%;
  height: 77%;
  display: flex;
  /* border: 1px solid; */
}
.content_content_small_left_one,
.content_content_small_left_two {
  width: 50%;
  height: 100%;
  /* border: 1px solid; */
}
.small_box_top,
.small_box_bottom {
  width: 100%;
  height: 50%;
  display: flex;
  padding-top: 1.5vh;
  /* border: 1px solid; */
}
.small_box_top_left {
  width: 35%;
  height: 100%;
  /* text-align: right; */
  padding-left: 15%;
  /* border: 1px solid red; */
}
.small_box_top_right {
  width: 65%;
  height: 100%;
  border-bottom: 1px solid #2c4aab;
  /* border: 1px solid red; */
}
.small_box_bottom_right {
  width: 65%;
  height: 100%;
  /* border: 1px solid red; */
}
.small_box_top_img {
  width: 2.5vw;
}
.small_box_top_right_text {
  font-size: 0.9vw;
  color: #19ecff;
}
.small_box_top_imgs {
  width: 70%;
  margin-top: 0.3vh;
}
.hygrometer {
  width: 100%;
  height: 100%;
  margin: 0 auto;
}
.echarts_temporary,
.echarts_fixed {
  width: 100%;
  height: 100%;
  margin: 0 auto;
}
.content_bottom_echarts {
  width: 100%;
  height: 90%;
  margin-top: -2%;
  /* border: 1px solid red; */
}
.echarts_category {
  width: 100%;
  height: 100%;
}
.text {
  height: 100%;
  display: flex;
  align-items: center;
  justify-content: center;
  /* border: 1px solid; */
}
.tab2_content_top,
.tab2_content_center,
.tab2_content_bottom {
  width: 100%;
  height: 22.5vh;
  margin-top: 2vh;
  padding-top: 1.5vh;
  background: url("../../assets/cbd_icon/two_long_bg.png");
  background-size: 100% 100%;
  /* border: 1px solid; */
}
.tab2_titles {
  width: 12vw;
  height: 4vh;
  text-align: center;
  line-height: 4.3vh;
  font-size: 0.9vw;
  color: #eff3f5;
  margin: 0 auto;
  background: url("../../assets/cbd_icon/small_bg.png");
  background-size: 100% 100%;
}
.tab2_boxs {
  width: 100%;
  height: 17vh;
  /* border: 1px solid;
   */
}
.lack,
.use,
.flow {
  width: 100%;
  height: 100%;
  margin: 0 auto;
}
.year_box {
  width: 100%;
  height: 70vh;
  margin-top: 4vh;
  background: url("../../assets/cbd_icon/year_bg.png");
  background-size: 100% 100%;
  /* border: 1px solid; */
}
.calendar {
  width: 100%;
  height: 100%;
  /* border: 1px solid red; */
}
</style>
<template>
  <div class="box">
    <button :class="show == true ? 'btn' : 'btn1'" @click="getFullCreeen">
      <Icon :type="show == true ? 'ios-expand' : 'ios-contract'" />
    </button>
    <!-- title标题 -->
    <div class="heads">
      <div class="head_title_bg">
        <div class="head_title1">停车资源历史分析</div>
        <div class="head_title2">Parking resources historical analysis</div>
      </div>
    </div>

    <!-- tab切换按钮 -->
    <div class="tab_left">
      <div
        :class="title_index == 1 ? 'tab_title' : 'tab_titles'"
        @click="tab_tile('1')"
      >
        <div class="text">分</div>
        <div class="text">布</div>
        <div class="text">规</div>
        <div class="text">律</div>
      </div>
      <div
        :class="title_index == 2 ? 'tab_title' : 'tab_titles'"
        @click="tab_tile('2')"
      >
        <div class="text">紧</div>
        <div class="text">缺</div>
        <div class="text">分</div>
        <div class="text">析</div>
      </div>
      <div
        :class="title_index == 3 ? 'tab_title' : 'tab_titles'"
        @click="tab_tile('3')"
      >
        <div class="text">全</div>
        <div class="text">年</div>
        <div class="text">车</div>
        <div class="text">流</div>
      </div>
    </div>
    <!-- 中间整体盒子 -->
    <div class="content">
      <!-- 操作框 -->
      <div class="content_top">
        <div class="content_top_top">
          <!-- 全部车场 -->
          <select
            v-model="park_code"
            class="all_car"
            :class="title_index != 3 ? 'all_car' : 'all_car2'"
            @change="getCouponSelected"
          >
            <option
              class="all_car1"
              v-for="item in cityList"
              :value="item.park_code"
              :key="item.park_code"
            >
              {{ item.park_name }}
            </option>
          </select>
          <!-- 年下拉框 -->
          <select
            v-show="title_index == 3"
            v-model="year"
            class="all_car"
            @change="getyear"
          >
            <option
              class="all_car1"
              v-for="item in yearlist"
              :value="item.year"
              :key="item.id"
            >
              {{ item.year }}
            </option>
          </select>

          <RadioGroup
            v-show="title_index == 3"
            v-model="radio3"
            @on-change="radio3_click"
            size="large"
            style="
              margin-left: 2%;
              color: #17d3e7;
              font-size: 1vw;
              margin-top: 0.5%;
            "
            color="#17D3E7"
          >
            <Radio label="全年车流量"></Radio>
            <Radio label="紧缺场次"></Radio>
          </RadioGroup>
          <!-- 日周月下拉框 -->
          <select
            v-model="model2"
            class="all_car"
            @change="getCouponSelected2"
            v-show="title_index != 3"
          >
            <option
              class="all_car1"
              v-for="item in cityList2"
              :value="item.value"
              :key="item.value"
            >
              {{ item.label }}
            </option>
          </select>
          <!-- 开始时间选择器 -->
          <DatePicker
            v-show="title_index != 3"
            type="date"
            v-model="time_start"
            class="all_car"
            placeholder="Select date"
            :clearable="false"
            @on-change="change_start_time"
          ></DatePicker>
          <!-- 结束时间选择器 -->
          <DatePicker
            v-show="title_index != 3"
            v-model="time_end"
            @on-change="change_end_time"
            type="date"
            :disabled="time2_disable"
            class="all_car"
            placeholder="Select date"
            :clearable="false"
          ></DatePicker>
          <!-- 搜索按钮 -->
          <div
            class="search"
            v-show="search_show && title_index != 3"
            @click="search"
          >
            搜索
          </div>
          <!-- 工作日单选框 -->
          <RadioGroup
            v-show="title_index == 1"
            v-model="animal"
            @on-change="radio_click"
            size="large"
            style="
              margin-left: 2%;
              color: #17d3e7;
              font-size: 1vw;
              margin-top: 0.5%;
            "
            color="#17D3E7"
          >
            <Radio label="全部"></Radio>
            <Radio label="工作日"></Radio>
            <Radio label="休息日"></Radio>
          </RadioGroup>
        </div>
        <div class="content_top_bottom">
          <div :class="title_index != 3 ? 'start_end_time' : 'start_end_time1'">
            <span style="margin-left: 12%; font-weight: bold">分析区间</span>
            <span style="margin-left: 8%">{{ start_time }}</span>
            <span style="margin-left: 4%">-</span>
            <span style="margin-left: 4%">{{ end_time }}</span>
          </div>
          <div
            :class="
              title_index != 3
                ? 'content_top_bottom_text'
                : 'content_top_bottom_text1'
            "
          >
            <span style="margin-right: 0%" v-show="title_index == 3"
              >{{ year }}&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;年</span
            >
            <span style="margin-left: 0%">车辆出入共计</span>
            <!-- <count-to
              style="margin-left: 3%"
              :start-val="startValue1"
              :end-val="endValue1"
              :useEasing="true"
              :duration="duration"
            ></count-to> -->
            <!-- <span style="margin-left: 3%"></span> -->
            <count-to
              style="margin-left: 3%"
              :start-val="startValue2"
              :end-val="endValue2"
              :useEasing="true"
              :duration="duration"
              suffix="台/次"
            ></count-to>
            <span style="margin-left: 3%">发生车位紧缺</span>
            <count-to
              style="margin-left: 3%"
              :start-val="startValue3"
              :end-val="endValue3"
              :useEasing="true"
              :duration="duration"
            ></count-to>
            <span style="margin-left: 3%">场/次，共计</span>
            <count-to
              style="margin-left: 3%"
              :start-val="startValue4"
              :end-val="endValue4"
              :useEasing="true"
              :duration="duration"
              suffix="小时"
            ></count-to>
          </div>
        </div>
      </div>

      <!-- 分布规律tab1 -->
      <div class="content_content" v-show="title_index == 1">
        <div class="content_content_left">
          <div class="content_content_small_title">车流占比</div>
          <div class="content_content_small_left">
            <div class="content_content_small_left_one">
              <div class="small_box_top">
                <div class="small_box_top_left">
                  <img
                    class="small_box_top_img"
                    src="../../assets/cbd_icon/blue_car.png"
                    alt=""
                  />
                </div>
                <div class="small_box_top_right">
                  <div class="small_box_top_right_text">临停车流总数</div>
                  <count-to
                    style="font-size: 1.5vw; color: #19ecff; font-weight: bold"
                    :start-val="startValue5"
                    :end-val="endValue5"
                    :useEasing="true"
                    :duration="duration"
                  ></count-to>
                  <span
                    style="font-size: 1vw; color: #19ecff; font-weight: bold"
                    >台/次</span
                  >
                  <img
                    class="small_box_top_imgs"
                    src="../../assets/cbd_icon/blue_car_s.png"
                    alt=""
                  />
                </div>
              </div>
              <div class="small_box_bottom">
                <div class="small_box_top_left">
                  <img
                    class="small_box_top_img"
                    src="../../assets/cbd_icon/orange_car.png"
                    alt=""
                  />
                </div>
                <div class="small_box_bottom_right">
                  <div class="small_box_top_right_text" style="color: #de6808">
                    固定车流总数
                  </div>
                  <count-to
                    style="font-size: 1.5vw; color: #de6808; font-weight: bold"
                    :start-val="startValue6"
                    :end-val="endValue6"
                    :useEasing="true"
                    :duration="duration"
                  ></count-to>
                  <span
                    style="font-size: 1vw; color: #de6808; font-weight: bold"
                    >台/次</span
                  >
                  <img
                    class="small_box_top_imgs"
                    src="../../assets/cbd_icon/orange_car_s.png"
                    alt=""
                  />
                </div>
              </div>
            </div>
            <div class="content_content_small_left_two">
              <!-- 水球图 -->
              <div class="hygrometer" ref="hygrometer"></div>
            </div>
          </div>
        </div>
        <div class="content_content_right">
          <div class="content_content_small_title">时长分布</div>
          <div class="content_content_small_left">
            <div class="content_content_small_left_one">
              <div class="echarts_temporary" ref="echarts_temporary"></div>
            </div>
            <div class="content_content_small_left_two">
              <div class="echarts_fixed" ref="echarts_fixed"></div>
            </div>
          </div>
        </div>
      </div>
      <!-- 堆叠柱状图 -->
      <div class="content_bottom" v-show="title_index == 1">
        <div class="content_content_small_title">时段分布</div>
        <div class="content_bottom_echarts">
          <div class="echarts_category" ref="echarts_category"></div>
        </div>
      </div>

      <!-- 紧缺分析tab2 -->
      <div v-show="title_index == 2">
        <div class="tab2_content_top">
          <div class="tab2_titles">车位紧缺分析</div>
          <div class="tab2_boxs">
            <div class="lack" ref="lack"></div>
          </div>
        </div>
        <div class="tab2_content_center">
          <div class="tab2_titles">车位使用率分析</div>
          <div class="tab2_boxs">
            <div class="use" ref="use"></div>
          </div>
        </div>
        <div class="tab2_content_bottom">
          <div class="tab2_titles">车位流量分析</div>
          <div class="tab2_boxs">
            <div class="flow" ref="flow"></div>
          </div>
        </div>
      </div>
      <!-- 全年车流tab3 -->
      <div v-show="title_index == 3" class="year_box">
        <div class="calendar" ref="calendar"></div>
      </div>
    </div>
  </div>
</template>
<script>
import url from "@/api/url";
import axios from "@/libs/api.request";
import axios1 from "@/libs/api.request.json";
import screenfull from "screenfull";
import countTo from "vue-count-to";
function getWeekDay(dateString) {
  let dateStringReg = /^\d{4}[/-]\d{1,2}[/-]\d{1,2}$/;

  if (dateString.match(dateStringReg)) {
    let presentDate = new Date(dateString),
      today = presentDate.getDay() !== 0 ? presentDate.getDay() : 7;

    return Array.from(new Array(7), function (val, index) {
      return formatDate(
        new Date(
          presentDate.getTime() - (today - index - 1) * 24 * 60 * 60 * 1000
        )
      );
    });
  } else {
    throw new Error('dateString should be like "yyyy-mm-dd" or "yyyy/mm/dd"');
  }

  function formatDate(date) {
    return (
      date.getFullYear() + "-" + (date.getMonth() + 1) + "-" + date.getDate()
    );
  }
}
//获取今天是周几
var weekDay = ["周日", "周一", "周二", "周三", "周四", "周五", "周六"];
function time1(t) {
  let date = new Date(t);
  let Y = date.getFullYear();
  let M =
    date.getMonth() + 1 < 10
      ? "0" + (date.getMonth() + 1)
      : date.getMonth() + 1;
  let D = date.getDate() < 10 ? "0" + date.getDate() : date.getDate();
  let h = date.getHours() < 10 ? "0" + date.getHours() : date.getHours();
  let m = date.getMinutes() < 10 ? "0" + date.getMinutes() : date.getMinutes();

  return Y + "-" + M + "-" + D;
}

//格式化日期：yyyy-MM-dd

function formatDate(date) {
  var myyear = date.getFullYear();
  var mymonth = date.getMonth() + 1;
  var myweekday = date.getDate();

  if (mymonth < 10) {
    mymonth = "0" + mymonth;
  }
  if (myweekday < 10) {
    myweekday = "0" + myweekday;
  }
  return myyear + "-" + mymonth + "-" + myweekday;
}

//获得某月的开始日期
function getMonthStartDate(paraYear, paraMonth) {
  var monthStartDate = new Date(paraYear, paraMonth, 1);
  return formatDate(monthStartDate);
}
//获得某月的天数
function getMonthDays(paraYear, paraMonth) {
  var monthStartDate = new Date(paraYear, paraMonth, 1);
  var monthEndDate = new Date(paraYear, paraMonth + 1, 1);
  var days = (monthEndDate - monthStartDate) / (1000 * 60 * 60 * 24);
  return days;
}
//获得某月的结束日期
function getMonthEndDate(paraYear, paraMonth) {
  var monthEndDate = new Date(
    paraYear,
    paraMonth,
    getMonthDays(paraYear, paraMonth)
  );
  return formatDate(monthEndDate);
}
export default {
  components: {
    countTo,
  },
  data() {
    return {
      start_time: "", //分析区间开始时间
      end_time: "", //分析区间 结束时间
      search_show: false, //搜索按钮显示/隐藏
      time2_disable: true, //结束时间选择器禁用标识
      time_end: new Date(), //时间选择器 结束时间
      time_start: new Date(), //时间选择器 开始时间
      show: true, //全屏/退出全屏按钮标识
      radio3: "全年车流量",
      startValue1: 0,
      endValue1: 0,
      startValue2: 0,
      endValue2: 0,
      startValue3: 0,
      endValue3: 0,
      startValue4: 0,
      endValue4: 0,
      startValue5: 0,
      endValue5: 0,
      startValue6: 0,
      endValue6: 0,
      duration: 3000,
      data: "",
      title_index: 1,
      cityList: [], //车场列表
      park_code: "", //车场
      year: "",
      yearlist: [
        {
          year: "2019",
          id: "2019",
        },
        {
          year: "2020",
          id: "2020",
        },
        {
          year: "2021",
          id: "2021",
        },
        {
          year: "2022",
          id: "2022",
        },
        {
          year: "2023",
          id: "2023",
        },
        {
          year: "2024",
          id: "2024",
        },
      ],
      cityList2: [
        {
          value: "日总览",
          label: "日总览",
        },
        {
          value: "周总览",
          label: "周总览",
        },
        {
          value: "月总览",
          label: "月总览",
        },
        {
          value: "自定义",
          label: "自定义",
        },
      ],
      model2: "周总览",
      animal: "全部",
    };
  },
  mounted() {
    let that = this;
    if (this.title_index == 1) {
      this.category();
      this.echarts();
      this.temporary();
      this.fixed();
    } else if (this.title_index == 2) {
      this.lacks();
      this.uses();
      this.flows();
    } else if (this.title_index == 3) {
      this.getyear();
      this.calendars();
    }
    // //水球图
    // this.echarts();
    // //临停图
    // this.temporary();
    // //固定图
    // this.fixed();
    // //堆叠柱状图
    // this.category();
    // //车位紧缺分析
    // that.lacks();
    // //车位使用率分析
    // that.uses();
    // //车流量分析
    // that.flows();
    // //全年车流日历图
    // that.calendars();
    window.onresize = () => {
      // 全屏下监控是否按键了ESC
      if (!that.checkFull()) {
        that.show = true;
        that.$root.event.$emit("show", true);
      }
    };
    // const iframe = document.querySelector("#ifr");
    // 处理兼容行问题
    // if (iframe.attachEvent) {
    //   iframe.attachEvent("onload", function () {
    //     // iframe加载完毕以后执行操作
    //     console.log("iframe已加载完毕");
    //     setTimeout(() => {
    //       that.loading = false;
    //     }, 2000);
    //   });
    // } else {
    //   iframe.onload = function () {
    //     // iframe加载完毕以后执行操作
    //     console.log("iframe已加载完毕");
    //     setTimeout(() => {
    //       that.loading = false;
    //     }, 2000);
    //   };
    // }
  },
  created() {
    this.park_list();
    this.getCouponSelected2();
    this.getyear();
    this.model2 = this.cityList2[0].value;
  },
  methods: {
    park_list() {
      axios
        .request({
          url: url.url.park_list,
          params: {
            code: "park-list",
            type: 1,
          },
          method: "get",
        })
        .then((res) => {
          this.cityList = res.data;
          this.park_code = this.cityList[0].park_code;
          // console.log(res);
        });
    },
    //tab页点击
    tab_tile(number) {
      this.title_index = number;
      if (this.title_index == 1) {
        this.getCouponSelected2();
        setTimeout(() => {
          this.category();
          this.echarts();
          this.temporary();
          this.fixed();
        }, 500);
      } else if (this.title_index == 2) {
        this.getCouponSelected2();
        setTimeout(() => {
          this.lacks();
          this.uses();
          this.flows();
        }, 500);
      } else if (this.title_index == 3) {
        this.getyear();
        this.calendars();
      }
      setTimeout(() => {
        if (this.hygrometer) {
          this.hygrometer.resize(); //刷新水球图
        }
        if (this.echarts_temporary) {
          this.echarts_temporary.resize(); //刷新临停图
        }
        if (this.echarts_fixed) {
          this.echarts_fixed.resize(); //刷新固定图
        }
        if (this.echarts_category) {
          this.echarts_category.resize(); //刷新时段分布
        }

        if (this.lack) {
          this.lack.resize(); //刷新车位紧缺分析
        }

        if (this.use) {
          this.use.resize(); //刷新车位使用率分析
        }

        if (this.flow) {
          this.flow.resize(); //刷新车流量分析
        }
        if (this.calendar) {
          this.calendar.resize(); //刷新全年车流日历图
        }
      }, 100);
    },
    // 开始时间点击
    change_start_time() {
      // console.log(this.time_start);
      var myDate = new Date(Date.parse(time1(this.time_start)));
      if (this.model2 == "日总览") {
        this.start_time =
          time1(this.time_start) + "(" + weekDay[myDate.getDay()] + ")";
        this.end_time =
          time1(this.time_start) + "(" + weekDay[myDate.getDay()] + ")";
      } else if (this.model2 == "周总览") {
        this.start_time =
          time1(getWeekDay(time1(this.time_start))[0]) + "(周一)";
        this.end_time = time1(getWeekDay(time1(this.time_start))[6]) + "(周日)";
      } else if (this.model2 == "月总览") {
        let starttime = time1(this.time_start).split("-");

        //获取某天是周几
        var weekDay1 = ["周日", "周一", "周二", "周三", "周四", "周五", "周六"];
        var myDate1 = new Date(
          Date.parse(getMonthStartDate(starttime[0], starttime[1] - 1))
        );

        this.start_time =
          getMonthStartDate(starttime[0], starttime[1] - 1) +
          "(" +
          weekDay1[myDate1.getDay()] +
          ")";
        let endtime = time1(this.time_start).split("-");
        var myDate2 = new Date(
          Date.parse(getMonthEndDate(endtime[0], endtime[1] - 1))
        );
        this.end_time =
          getMonthEndDate(endtime[0], endtime[1] - 1) +
          "(" +
          weekDay1[myDate2.getDay()] +
          ")";
      } else if (this.model2 == "自定义") {
        this.start_time =
          time1(this.time_start) + "(" + weekDay[myDate.getDay()] + ")";
      }
      if (this.model2 != "自定义") {
        this.cars_num();
        if (this.title_index == 1) {
          this.category();
          this.echarts();
          this.temporary();
          this.fixed();
        } else if (this.title_index == 2) {
          this.lacks();
          this.uses();
          this.flows();
        }
      }
    },
    // 结束时间点击
    change_end_time() {
      // console.log(this.time_end);
      var myDate = new Date(Date.parse(time1(this.time_end)));
      this.end_time =
        time1(this.time_end) + "(" + weekDay[myDate.getDay()] + ")";
    },
    // 车场下拉框
    getCouponSelected() {
      // console.log(this.park_code);
      this.cars_num();
      if (this.title_index == 1) {
        this.category();
        this.echarts();
        this.temporary();
        this.fixed();
      } else if (this.title_index == 2) {
        this.lacks();
        this.uses();
        this.flows();
      } else if (this.title_index == 3) {
        this.calendars();
      }
    },
    // 日周月下拉框
    getCouponSelected2() {
      let that = this;
      function time() {
        let date = new Date(that.time_start);
        let Y = date.getFullYear();
        let M =
          date.getMonth() + 1 < 10
            ? "0" + (date.getMonth() + 1)
            : date.getMonth() + 1;
        let D = date.getDate() < 10 ? "0" + date.getDate() : date.getDate();
        let h = date.getHours() < 10 ? "0" + date.getHours() : date.getHours();
        let m =
          date.getMinutes() < 10 ? "0" + date.getMinutes() : date.getMinutes();

        return Y + "-" + M + "-" + D;
      }
      var myDate = new Date(Date.parse(time()));
      // console.log(this.model2);
      if (this.model2 == "自定义") {
        this.time2_disable = false;
        this.search_show = true;
      } else {
        this.time2_disable = true;
        this.search_show = false;
      }
      if (this.model2 == "日总览") {
        this.start_time = time() + "(" + weekDay[myDate.getDay()] + ")";
        this.end_time = time() + "(" + weekDay[myDate.getDay()] + ")";
      } else if (this.model2 == "周总览") {
        this.start_time = time1(getWeekDay(time())[0]) + "(周一)";
        this.end_time = time1(getWeekDay(time())[6]) + "(周日)";
      } else if (this.model2 == "月总览") {
        let starttime = time().split("-");

        //获取某天是周几
        var weekDay1 = ["周日", "周一", "周二", "周三", "周四", "周五", "周六"];
        var myDate1 = new Date(
          Date.parse(getMonthStartDate(starttime[0], starttime[1] - 1))
        );

        this.start_time =
          getMonthStartDate(starttime[0], starttime[1] - 1) +
          "(" +
          weekDay1[myDate1.getDay()] +
          ")";
        let endtime = time().split("-");
        var myDate2 = new Date(
          Date.parse(getMonthEndDate(endtime[0], endtime[1] - 1))
        );
        this.end_time =
          getMonthEndDate(endtime[0], endtime[1] - 1) +
          "(" +
          weekDay1[myDate2.getDay()] +
          ")";
      }
      if (this.model2 != "自定义") {
        this.cars_num();
        if (this.title_index == 1) {
          this.category();
          this.echarts();
          this.temporary();
          this.fixed();
        } else if (this.title_index == 2) {
          this.lacks();
          this.uses();
          this.flows();
        }
      }
    },
    //年下拉框
    getyear() {
      let that = this;
      if (!this.year) {
        let date = new Date();
        let y = date.getFullYear();
        this.year = y;
        console.log(y);
      }
      function time_end() {
        return that.year + "-" + "12" + "-" + "31";
      }
      function time_start() {
        return that.year + "-" + "01" + "-" + "01";
      }
      //获取今天是周几
      var weekDay = ["周日", "周一", "周二", "周三", "周四", "周五", "周六"];
      var myDate_end = new Date(Date.parse(time_end()));
      var myDate_start = new Date(Date.parse(time_start()));
      that.end_time = time_end() + "(" + weekDay[myDate_end.getDay()] + ")";
      that.start_time =
        time_start() + "(" + weekDay[myDate_start.getDay()] + ")";
      that.calendars();
      that.cars_num();
    },
    //搜索
    search() {
      // console.log("搜索");
      this.cars_num();
      if (this.title_index == 1) {
        this.category();
        this.echarts();
        this.temporary();
        this.fixed();
      } else if (this.title_index == 2) {
        this.lacks();
        this.uses();
        this.flows();
      }
    },
    // 工作日、休息日点击
    radio_click() {
      this.cars_num();
      this.category();
      this.echarts();
      this.temporary();
      this.fixed();
      // console.log(this.animal);
    },
    // 车流量点击
    radio3_click() {
      console.log(this.radio3);
      this.calendars();
    }, //统计区间数据
    cars_num() {
      let that = this;
      // 统计区间共有多少辆车
      // axios
      //   .request({
      //     url: url.url.cars_num,
      //     params: {
      //       parkCode: that.park_code,
      //       startDate: time1(that.start_time),
      //       endDate: time1(that.end_time),
      //       workType: that.animal,
      //       code: "cars-num",
      //       type: 2,
      //     },
      //     methods: "get",
      //   })
      //   .then((res) => {
      //     that.endValue1 = res.data[0].value;
      //     that.startValue1 = that.endValue1;
      //   });
      // if (this.title_index) {
      //   return;
      // }

      // 出入共计多少次
      axios
        .request({
          url: url.url.cars_num,
          params: {
            parkCode: that.park_code,
            startDate: time1(that.start_time),
            endDate: time1(that.end_time),
            workType: that.animal,
            code: "total-times",
            type: 5,
          },
          methods: "get",
        })
        .then((res) => {
          // console.log(res);
          that.endValue2 = res.data[0].value;
          that.startValue2 = that.endValue1;
        });

      // 紧缺次数
      axios
        .request({
          url: url.url.cars_num,
          params: {
            parkCode: that.park_code,
            startDate: time1(that.start_time),
            endDate: time1(that.end_time),
            workType: that.animal,
            code: "shortage-times",
            type: 3,
          },
          methods: "get",
        })
        .then((res) => {
          // console.log(res);
          that.endValue3 = res.data[0].value;
          that.startValue3 = that.endValue1;
        });

      // 紧缺小时
      axios
        .request({
          url: url.url.cars_num,
          params: {
            parkCode: that.park_code,
            startDate: time1(that.start_time),
            endDate: time1(that.end_time),
            workType: that.animal,
            code: "shortage-hour",
            type: 3,
          },
          methods: "get",
        })
        .then((res) => {
          // console.log(res);
          that.endValue4 = res.data[0].value;
          that.startValue4 = that.endValue1;
        });
      if (that.title_index == 1) {
        //临停车流总数
        axios
          .request({
            url: url.url.cars_num,
            params: {
              parkCode: that.park_code,
              startDate: time1(that.start_time),
              endDate: time1(that.end_time),
              workType: that.animal,
              code: "temp-flow-sum",
              type: 5,
            },
            methods: "get",
          })
          .then((res) => {
            // console.log(res);
            that.endValue5 = res.data[0].value;
            that.startValue5 = that.endValue1;
          });

        //固定车流总数
        axios
          .request({
            url: url.url.cars_num,
            params: {
              parkCode: that.park_code,
              startDate: time1(that.start_time),
              endDate: time1(that.end_time),
              workType: that.animal,
              code: "fix-flow-sum",
              type: 5,
            },
            methods: "get",
          })
          .then((res) => {
            // console.log(res);
            that.endValue6 = res.data[0].value;
            that.startValue6 = that.endValue1;
          });
      }
    },
    checkFull() {
      var isFull =
        window.fullScreen ||
        document.webkitIsFullScreen ||
        document.msFullscreenEnabled;
      if (isFull === undefined) {
        isFull = false;
      }
      return isFull;
    },
    //全屏事件
    getFullCreeen() {
      if (screenfull.isEnabled) {
        screenfull.toggle();
      }
      if (this.show == true) {
        this.show = false;
        this.show1 = false;
      } else {
        this.show = true;
        this.show1 = true;
      }
      this.$root.event.$emit("show", this.show);
      setTimeout(() => {
        if (this.hygrometer) {
          this.hygrometer.resize(); //刷新水球图
        }
        if (this.echarts_temporary) {
          this.echarts_temporary.resize(); //刷新临停图
        }
        if (this.echarts_fixed) {
          this.echarts_fixed.resize(); //刷新固定图
        }
        if (this.echarts_category) {
          this.echarts_category.resize(); //刷新时段分布
        }

        if (this.lack) {
          this.lack.resize(); //刷新车位紧缺分析
        }

        if (this.use) {
          this.use.resize(); //刷新车位使用率分析
        }

        if (this.flow) {
          this.flow.resize(); //刷新车流量分析
        }
        if (this.calendar) {
          this.calendar.resize(); //刷新全年车流日历图
        }
      }, 100);
    },
    // 水球图 车流占比
    echarts() {
      let that = this;
      this.hygrometer = this.$echarts.init(this.$refs.hygrometer);
      // 车流占比水位图
      axios
        .request({
          url: url.url.cars_num,
          params: {
            parkCode: that.park_code,
            startDate: time1(that.start_time),
            endDate: time1(that.end_time),
            workType: that.animal,
            code: "traffic-flow-proport",
            type: 5,
          },
          methods: "get",
        })
        .then((res) => {
          // console.log(res, "水球图");
          let option = {
            title: {
              text: "临停车流占比",
              bottom: "30%",
              left: "center",
              textStyle: {
                // 文本样式
                fontSize: 18,
                color: "#61F2FF",
                opacity: "0.8",
              },
            },
            series: [
              {
                type: "liquidFill",
                radius: "75%",
                data: [res.data[0].value ? res.data[0].value : 0],
                direction: "right", // 波浪移动的速度  两个参数  left 从右往左 right 从左往右
                shape: "circle",
                label: {
                  normal: {
                    color: "#61F2FF",
                    opacity: "0.8",
                    insideColor: "transparent",
                    textStyle: {
                      fontSize: 45,
                      fontWeight: "bold",
                    },
                  },
                },
                outline: {
                  show: true,
                  borderDistance: 5,
                  itemStyle: {
                    borderColor: "rgba(67,209,100,1)",
                    borderWidth: 2,
                  },
                },
                backgroundStyle: {
                  color: "#101F3E", // 水球未到的背景颜色
                  opacity: 0,
                },
                // 图形样式
                itemStyle: {
                  color: "#37BA8F", // 水球显示的背景颜色
                  opacity: 1, // 波浪的透明度
                  shadowBlur: 10, // 波浪的阴影范围
                },
                // 图形的高亮样式
                emphasis: {
                  itemStyle: {
                    opacity: 0.9, // 鼠标经过波浪颜色的透明度
                  },
                },
                // amplitude: 90, //振幅
              },
            ],
          };
          // console.log("option", option);
          this.hygrometer.setOption(option);
        });
    },
    // 临停图 时长分布
    temporary() {
      let that = this;
      this.echarts_temporary = this.$echarts.init(this.$refs.echarts_temporary);
      axios
        .request({
          url: url.url.cars_num,
          params: {
            parkCode: that.park_code,
            startDate: time1(that.start_time),
            endDate: time1(that.end_time),
            workType: that.animal,
            code: "temp-distribution",
            type: 6,
          },
          methods: "get",
        })
        .then((res) => {
          let datas = [];
          let data1 = false;
          let data2 = false;
          let data3 = false;
          let data4 = false;
          let data5 = false;
          let data6 = false;
          let data7 = false;
          let data8 = false;
          res.data.map((res, index) => {
            if (res.x == 1) {
              datas.push({
                value: res.y,
                name: "1小时之内",
              });
              data1 = true;
            }
            if (res.x == 2) {
              datas.push({
                value: res.y,
                name: "2小时之内",
              });
              data2 = true;
            }
            if (res.x == 3) {
              datas.push({
                value: res.y,
                name: "3小时之内",
              });
              data3 = true;
            }
            if (res.x == 4) {
              datas.push({
                value: res.y,
                name: "4小时之内",
              });
              data4 = true;
            }
            if (res.x == 5) {
              datas.push({
                value: res.y,
                name: "4-8小时",
              });
              data5 = true;
            }
            if (res.x == 6) {
              datas.push({
                value: res.y,
                name: "8-12小时",
              });
              data6 = true;
            }
            if (res.x == 7) {
              datas.push({
                value: res.y,
                name: "12-24小时",
              });
              data7 = true;
            }
            if (res.x == 8) {
              datas.push({
                value: res.y,
                name: "一天以上",
              });
              data8 = true;
            }
          });
          if (data1 == false) {
            datas.splice(0, 0, {
              value: 0,
              name: "1小时之内",
            });
          }
          if (data2 == false) {
            datas.splice(1, 0, {
              value: 0,
              name: "2小时之内",
            });
          }
          if (data3 == false) {
            datas.splice(2, 0, {
              value: 0,
              name: "3小时之内",
            });
          }
          if (data4 == false) {
            datas.splice(3, 0, {
              value: 0,
              name: "4小时之内",
            });
          }
          if (data5 == false) {
            datas.splice(4, 0, {
              value: 0,
              name: "4-8小时",
            });
          }
          if (data6 == false) {
            datas.splice(5, 0, {
              value: 0,
              name: "8-12小时",
            });
          }
          if (data7 == false) {
            datas.splice(6, 0, {
              value: 0,
              name: "12-24小时",
            });
          }
          if (data8 == false) {
            datas.splice(7, 0, {
              value: 0,
              name: "一天以上",
            });
          }
          let option = {
            color: [
              "#00D88A",
              "#4068CB",
              "#39C5B5",
              "#FEB52A",
              "#199AF4",
              "#00E4ED",
              "#8256E7",
              "#EB704A",
            ],
            title: {
              text: "临停",
              bottom: "0%",
              left: "center",
              textStyle: {
                // 文本样式
                fontSize: 20,
                color: "#FFF",
                opacity: "1",
              },
            },
            tooltip: {
              trigger: "item",
              formatter: "{b}：{d}%",
              backgroundColor: "rgba(0,0,0,.5)",
              textStyle: {
                //提示文本的样式
                color: "#fff",
                fontsize: 12,
              },
            },
            legend: {
              show: false,
            },
            toolbox: {
              show: false,
              feature: {
                mark: { show: false },
                dataView: { show: false, readOnly: false }, //表格
                restore: { show: false }, //刷新
                saveAsImage: { show: false }, //下载
              },
            },
            series: [
              {
                name: "面积模式",
                type: "pie",
                radius: ["30%", "60%"],
                center: ["50%", "45%"],
                roseType: "area",
                itemStyle: {
                  borderRadius: 0,
                },

                data: datas,
                itemStyle: {
                  emphasis: {
                    // shadowBlur: 10,
                    // shadowOffsetX: 0,
                    // shadowColor: "rgba(0, 0, 0, 5)",
                    // color: "white",
                  },
                  normal: {
                    label: {
                      show: true,
                      formatter: "{d}%\n{b} ",
                    },
                    labelLine: { show: true },
                  },
                },
                label: {
                  normal: {
                    textStyle: {
                      color: "white",
                    },
                  },
                },
              },
            ],
          };
          this.echarts_temporary.setOption(option);
        });
    },
    // 固定图  时长分布
    fixed() {
      let that = this;
      this.echarts_fixed = this.$echarts.init(this.$refs.echarts_fixed);
      axios
        .request({
          url: url.url.cars_num,
          params: {
            parkCode: that.park_code,
            startDate: time1(that.start_time),
            endDate: time1(that.end_time),
            workType: that.animal,
            code: "fix-distribution",
            type: 6,
          },
          methods: "get",
        })
        .then((res) => {
          let datas = [];
          let data1 = false;
          let data2 = false;
          let data3 = false;
          let data4 = false;
          let data5 = false;
          let data6 = false;
          let data7 = false;
          let data8 = false;
          res.data.map((res, index) => {
            if (res.x == 1) {
              datas.push({
                value: res.y,
                name: "1小时之内",
              });
              data1 = true;
            }
            if (res.x == 2) {
              datas.push({
                value: res.y,
                name: "2小时之内",
              });
              data2 = true;
            }
            if (res.x == 3) {
              datas.push({
                value: res.y,
                name: "3小时之内",
              });
              data3 = true;
            }
            if (res.x == 4) {
              datas.push({
                value: res.y,
                name: "4小时之内",
              });
              data4 = true;
            }
            if (res.x == 5) {
              datas.push({
                value: res.y,
                name: "4-8小时",
              });
              data5 = true;
            }
            if (res.x == 6) {
              datas.push({
                value: res.y,
                name: "8-12小时",
              });
              data6 = true;
            }
            if (res.x == 7) {
              datas.push({
                value: res.y,
                name: "12-24小时",
              });
              data7 = true;
            }
            if (res.x == 8) {
              datas.push({
                value: res.y,
                name: "一天以上",
              });
              data8 = true;
            }
          });
          if (data1 == false) {
            datas.splice(0, 0, {
              value: 0,
              name: "1小时之内",
            });
          }
          if (data2 == false) {
            datas.splice(1, 0, {
              value: 0,
              name: "2小时之内",
            });
          }
          if (data3 == false) {
            datas.splice(2, 0, {
              value: 0,
              name: "3小时之内",
            });
          }
          if (data4 == false) {
            datas.splice(3, 0, {
              value: 0,
              name: "4小时之内",
            });
          }
          if (data5 == false) {
            datas.splice(4, 0, {
              value: 0,
              name: "4-8小时",
            });
          }
          if (data6 == false) {
            datas.splice(5, 0, {
              value: 0,
              name: "8-12小时",
            });
          }
          if (data7 == false) {
            datas.splice(6, 0, {
              value: 0,
              name: "12-24小时",
            });
          }
          if (data8 == false) {
            datas.splice(7, 0, {
              value: 0,
              name: "一天以上",
            });
          }
          // console.log(datas, "固定图");
          let option = {
            color: [
              "#00D88A",
              "#4068CB",
              "#39C5B5",
              "#FEB52A",
              "#199AF4",
              "#00E4ED",
              "#8256E7",
              "#EB704A",
            ],
            title: {
              text: "固定",
              bottom: "0%",
              left: "center",
              textStyle: {
                // 文本样式
                fontSize: 20,
                color: "#FFF",
                opacity: "1",
              },
            },
            tooltip: {
              trigger: "item",
              formatter: "{b}：{d}%",
              backgroundColor: "rgba(0,0,0,.5)",
              textStyle: {
                //提示文本的样式
                color: "#fff",
                fontsize: 12,
              },
            },
            legend: {
              show: false,
            },
            toolbox: {
              show: false,
              feature: {
                mark: { show: false },
                dataView: { show: false, readOnly: false }, //表格
                restore: { show: false }, //刷新
                saveAsImage: { show: false }, //下载
              },
            },
            series: [
              {
                name: "面积模式",
                type: "pie",
                radius: ["30%", "60%"],
                center: ["50%", "45%"],
                roseType: "area",
                data: datas,
                itemStyle: {
                  normal: {
                    label: {
                      show: true,
                      formatter: "{d}%\n{b} ",
                    },
                    labelLine: { show: true },
                  },
                },
                label: {
                  normal: {
                    textStyle: {
                      color: "white",
                    },
                  },
                },
              },
            ],
          };
          this.echarts_fixed.setOption(option);
        });
    },
    //堆叠柱状图 时段分布
    category() {
      let that = this;
      this.echarts_category = this.$echarts.init(this.$refs.echarts_category);
      axios
        .request({
          url: url.url.cars_num,
          params: {
            parkCode: that.park_code,
            startDate: time1(that.start_time),
            endDate: time1(that.end_time),
            workType: that.animal,
            code: "stack-distribution",
            type: 5,
          },
          methods: "get",
        })
        .then((res) => {
          // console.log(res, "时段分布");
          let names = [];
          let temporary_in = []; //临停入场
          let fixed_in = []; //固定入场
          let temporary_ou = []; //临停离场
          let fixed_out = []; //固定离场
          res.data.map((res) => {
            names.push(res.x);
            if (res.s == "临停入场") {
              temporary_in.push(res.y);
            } else if (res.s == "固定入场") {
              fixed_in.push(res.y);
            } else if (res.s == "临停离场") {
              temporary_ou.push(res.y);
            } else if (res.s == "固定离场") {
              fixed_out.push(res.y);
            }
          });
          function unique(arr) {
            return Array.from(new Set(arr));
          }
          names = unique(names);
          names.sort(function (a, b) {
            return a - b;
          });
          // console.log(names);
          let option = {
            color: ["#48E4A9", "#2853BD", "#0BB3FF", "#8256E7"],
            tooltip: {
              trigger: "axis",
              axisPointer: {
                // 坐标轴指示器，坐标轴触发有效
                type: "shadow", // 默认为直线，可选为：'line' | 'shadow'
              },
              backgroundColor: "rgba(0,0,0,.5)",
              textStyle: {
                //提示文本的样式
                color: "#fff",
                fontsize: 12,
              },
            },
            legend: {
              right: "5%",
              textStyle: {
                //提示文本的样式
                color: "#fff",
                fontsize: 12,
              },
              data: ["临停入场", "固定入场", "临停离场", "固定离场"],
            },
            grid: {
              left: "2%",
              right: "2%",
              bottom: "5%",
              containLabel: true,
            },
            xAxis: [
              {
                type: "category",
                axisLine: {
                  show: true,
                  lineStyle: {
                    color: "#15DCD5",
                    width: 2, //这里是为了突出显示加上的
                  },
                },
                data: names,
              },
            ],
            yAxis: [
              {
                type: "value",
                splitLine: { show: false },
                axisLine: {
                  show: true,
                  lineStyle: {
                    color: "#15DCD5",
                    width: 2, //这里是为了突出显示加上的
                  },
                },
              },
            ],
            series: [
              {
                name: "临停入场",
                type: "bar",
                stack: "入场",
                barWidth: 13,
                data: temporary_in,
              },
              {
                name: "固定入场",
                type: "bar",
                stack: "入场",
                barWidth: 13,
                data: fixed_in,
              },
              {
                name: "临停离场",
                type: "bar",
                stack: "离场",
                barWidth: 13,
                data: temporary_ou,
              },
              {
                name: "固定离场",
                type: "bar",
                stack: "离场",
                barWidth: 13,
                data: fixed_out,
              },
            ],
          };
          this.echarts_category.setOption(option);
        });
    },

    // tab2紧缺分析
    // 车位紧缺分析
    lacks() {
      let that = this;
      that.lack = that.$echarts.init(that.$refs.lack);
      // console.log(that.model2);
      axios
        .request({
          url: url.url.cars_lack,
          params: {
            parkCode: that.park_code,
            startDate: time1(that.start_time),
            endDate: time1(that.end_time),
            code: "shortage-analysis-day",
            code1: "shortage-analysis-week",
            code2: "shortage-analysis-month",
            type:
              that.model2 == "日总览"
                ? "1"
                : that.model2 == "周总览"
                ? "2"
                : "3",
          },
          methods: "get",
        })
        .then((res) => {
          // console.log(res, "紧缺分析");
          let names = [];
          let car_number = []; //紧缺车场数量
          let car_sessions = []; //车场紧缺场次
          res.data.map((reson) => {
            names.push(reson.x);
            car_number.push(reson.y);
            car_sessions.push(reson.z);
          });
          let week = [
            "星期一",
            "星期二",
            "星期三",
            "星期四",
            "星期五",
            "星期六",
            "星期日",
          ];
          let names1 = [];
          if (that.model2 == "周总览") {
            names.map((rese, index) => {
              names1.push(week[index]);
            });
          }
          let option = {
            color: ["#2798F2", "#C0504D"],
            tooltip: {
              trigger: "axis",
              backgroundColor: "rgba(0,0,0,.5)",
              textStyle: {
                //提示文本的样式
                color: "#fff",
                fontsize: 12,
              },
            },
            legend: {
              right: "5%",
              textStyle: {
                //提示文本的样式
                color: "rgba(255,255,255,.5)",
                fontsize: 12,
              },
              data: ["紧缺车场数量", "车场紧缺场次"],
            },
            grid: {
              left: "2%",
              right: "2%",
              bottom: "5%",
              top: "15%",
              containLabel: true,
            },
            xAxis: [
              {
                type: "category",
                data: that.model2 == "周总览" ? names1 : names,
                // axisPointer: {
                //     type: 'shadow'
                // }
                axisLine: {
                  show: true,
                  lineStyle: {
                    color: "#15DCD5",
                    width: 2, //这里是为了突出显示加上的
                  },
                },
              },
            ],
            yAxis: [
              {
                type: "value",
                splitLine: { show: false },
                axisLine: {
                  show: true,
                  lineStyle: {
                    color: "#15DCD5",
                    width: 2, //这里是为了突出显示加上的
                  },
                },
              },
              {
                type: "value",
                splitLine: { show: false },
                // name: '温度',
                axisLabel: {
                  formatter: "{value}",
                },
              },
            ],
            series: [
              {
                name: "紧缺车场数量",
                type: "bar",
                backgroundStyle: {
                  color: "rgba(110, 193, 244, 0.2)",
                },
                showBackground: true,
                data: car_number,
              },
              {
                name: "车场紧缺场次",
                type: "line",
                yAxisIndex: 1,
                data: car_sessions,
              },
            ],
          };
          this.lack.setOption(option);
        });
    },
    //车位使用率分析
    uses() {
      let that = this;
      that.use = that.$echarts.init(that.$refs.use);
      axios
        .request({
          url: url.url.cars_rate,
          params: {
            parkCode: that.park_code,
            startDate: time1(that.start_time),
            endDate: time1(that.end_time),
            code: "rate-analysis-day",
            code1: "rate-analysis-week",
            code2: "rate-analysis-month",
            type:
              that.model2 == "日总览"
                ? "1"
                : that.model2 == "周总览"
                ? "2"
                : "3",
          },
          methods: "get",
        })
        .then((res) => {
          // console.log(res, "使用率分析");
          let names = [];
          let car_fixed = []; //固定车位
          let car_temporary = []; //临停车位
          res.data.map((reson) => {
            if (reson.s == 0) {
              car_temporary.push(reson.y);
              names.push(reson.x);
            } else if (reson.s == 1) {
              car_fixed.push(reson.y);
            }
          });
          let week = [
            "星期一",
            "星期二",
            "星期三",
            "星期四",
            "星期五",
            "星期六",
            "星期日",
          ];
          let names1 = [];
          if (that.model2 == "周总览") {
            names.map((rese, index) => {
              names1.push(week[index]);
            });
          }
          let option = {
            color: ["#5E58B6", "#55EAB1"],
            tooltip: {
              trigger: "axis",
              backgroundColor: "rgba(0,0,0,.5)",
              textStyle: {
                //提示文本的样式
                color: "#fff",
                fontsize: 12,
              },
            },
            legend: {
              right: "5%",
              textStyle: {
                //提示文本的样式
                color: "rgba(255,255,255,.5)",
                fontsize: 12,
              },
              data: ["固定车位", "临停车位"],
            },
            grid: {
              left: "2%",
              right: "4%",
              bottom: "5%",
              top: "20%",
              containLabel: true,
            },
            toolbox: {
              show: false,
              feature: {
                dataView: { show: true, readOnly: false },
                magicType: { show: true, type: ["line", "bar"] },
                restore: { show: true },
                saveAsImage: { show: true },
              },
            },
            calculable: true,
            xAxis: [
              {
                type: "category",
                splitLine: { show: false },
                axisLine: {
                  show: true,
                  lineStyle: {
                    color: "#15DCD5",
                    width: 2, //这里是为了突出显示加上的
                  },
                },
                data: that.model2 == "周总览" ? names1 : names,
              },
            ],
            yAxis: [
              {
                type: "value",
                splitLine: { show: false },
                axisLine: {
                  show: true,
                  lineStyle: {
                    color: "#15DCD5",
                    width: 2, //这里是为了突出显示加上的
                  },
                },
              },
            ],
            series: [
              {
                name: "固定车位",
                type: "bar",
                data: car_fixed,
                markPoint: {
                  data: [
                    { type: "max", name: "最大值" },
                    { type: "min", name: "最小值" },
                  ],
                },
                markLine: {
                  data: [{ type: "average", name: "平均值" }],
                },
              },
              {
                name: "临停车位",
                type: "bar",
                data: car_temporary,
                markPoint: {
                  data: [
                    { type: "max", name: "最大值" },
                    { type: "min", name: "最小值" },
                  ],
                },
                markLine: {
                  data: [{ type: "average", name: "平均值" }],
                },
              },
            ],
          };
          that.use.setOption(option);
        });
    },
    //车流量分析
    flows() {
      let that = this;
      that.flow = that.$echarts.init(that.$refs.flow);
      axios
        .request({
          url: url.url.cars_flow,
          params: {
            parkCode: that.park_code,
            startDate: time1(that.start_time),
            endDate: time1(that.end_time),
            code: "flow-analysis-day",
            code1: "flow-analysis-week",
            code2: "flow-analysis-month",
            type:
              that.model2 == "日总览"
                ? "1"
                : that.model2 == "周总览"
                ? "2"
                : "3",
          },
          methods: "get",
        })
        .then((res) => {
          // console.log(res, "车流量分析");
          let names = [];
          let car_fixed = []; //固定车位
          let car_temporary = []; //临停车位
          res.data.map((reson) => {
            if (reson.s == 0) {
              car_temporary.push(reson.y);
              names.push(reson.x);
            } else if (reson.s == 1) {
              car_fixed.push(reson.y);
            }
          });
          let week = [
            "星期一",
            "星期二",
            "星期三",
            "星期四",
            "星期五",
            "星期六",
            "星期日",
          ];
          let names1 = [];
          if (that.model2 == "周总览") {
            names.map((rese, index) => {
              names1.push(week[index]);
            });
          }
          let option = {
            color: ["#2853BD", "#0BB3FF"],
            tooltip: {
              trigger: "axis",
              backgroundColor: "rgba(0,0,0,.5)",
              textStyle: {
                //提示文本的样式
                color: "#fff",
                fontsize: 12,
              },
            },
            legend: {
              right: "5%",
              textStyle: {
                //提示文本的样式
                color: "rgba(255,255,255,.5)",
                fontsize: 12,
              },
              data: ["固定车流", "临停车流"],
            },
            grid: {
              left: "2%",
              right: "4%",
              bottom: "5%",
              top: "20%",
              containLabel: true,
            },
            toolbox: {
              show: false,
              feature: {
                dataView: { show: true, readOnly: false },
                magicType: { show: true, type: ["line", "bar"] },
                restore: { show: true },
                saveAsImage: { show: true },
              },
            },
            calculable: true,
            xAxis: [
              {
                type: "category",
                splitLine: { show: false },
                axisLine: {
                  show: true,
                  lineStyle: {
                    color: "#15DCD5",
                    width: 2, //这里是为了突出显示加上的
                  },
                },
                data: that.model2 == "周总览" ? names1 : names,
              },
            ],
            yAxis: [
              {
                type: "value",
                splitLine: { show: false },
                axisLine: {
                  show: true,
                  lineStyle: {
                    color: "#15DCD5",
                    width: 2, //这里是为了突出显示加上的
                  },
                },
              },
            ],
            series: [
              {
                name: "固定车流",
                type: "bar",
                data: car_fixed,
                markPoint: {
                  data: [
                    { type: "max", name: "最大值" },
                    { type: "min", name: "最小值" },
                  ],
                },
                markLine: {
                  data: [{ type: "average", name: "平均值" }],
                },
              },
              {
                name: "临停车流",
                type: "bar",
                data: car_temporary,
                markPoint: {
                  data: [
                    { type: "max", name: "最大值" },
                    { type: "min", name: "最小值" },
                  ],
                },
                markLine: {
                  data: [{ type: "average", name: "平均值" }],
                },
              },
            ],
          };
          that.flow.setOption(option);
        });
    },
    calendars() {
      let that = this;
      that.calendar = that.$echarts.init(that.$refs.calendar);
      // 全年日历图
      axios
        .request({
          url: url.url.year_number,
          params: {
            type: that.radio3 == "全年车流量" ? 1 : 4,
            code:
              that.radio3 == "全年车流量"
                ? "calendar-year"
                : "calendar-shortage",
            startDate: that.year,
            parkCode: that.park_code,
          },
          methods: "get",
        })
        .then((res) => {
          // console.log(res, "全年日历图");
          let datas = [];
          res.data.map((rse) => {
            // console.log(rse);
            let data = [];
            data.push(rse.name);
            data.push(rse.value);
            datas.push(data);
          });
          // for (let i = 1; i <= 366 - datas.length; i++) {
          //   console.log(i);
          //   datas.push([0]);
          // }
          // 全年车流热力值;
          let max_number = 0;
          axios
            .request({
              url: url.url.year_number,
              params: {
                type: that.radio3 == "全年车流量" ? 1 : 4,
                code:
                  that.radio3 == "全年车流量"
                    ? "year-flow-hot-value"
                    : "shortage-times-hot-value",
                startDate: that.year,
                parkCode: that.park_code,
              },
              methods: "get",
            })
            .then((reson) => {
              // console.log(reson, "全年车流热力值");
              max_number = reson.data[0].value;

              let option = {
                tooltip: {
                  position: "top",
                  backgroundColor: "rgba(0,0,0,.5)",
                  textStyle: {
                    color: "white", //设置文字颜色
                    fontSize: 20,
                  },
                  //   extraCssText:'width:200px;height:60px;background:white;color:black;font-size:10px;',
                  formatter: function (p) {
                    var format = that.$echarts.format.formatTime(
                      "yyyy-MM-dd",
                      p.data[0]
                    );
                    return that.radio3 == "全年车流量"
                      ? "车流量" + "\n" + format + ": " + p.data[1]
                      : "紧缺次数" + "\n" + format + ": " + p.data[1];
                  },
                },
                visualMap: {
                  min: 0,
                  max: max_number,
                  type: "continuous",
                  calculable: true,
                  orient: "horizontal",
                  bottom: 25,
                  right: 300,
                  inRange: {
                    //红蓝相间
                    // color:['#5A8BC7', '#7E9FB9', '#A3B5A9', '#C9CB9D', '#ECE191', '#FEDC88', '#FCC080', '#FBA279', '#F98673', '#F7676C']

                    //红色色系
                    color: ["#00FF5B", "#0051FF", "#F3E700", "#FE2503"],
                  },
                  textStyle: {
                    color: "white",
                  },
                },
                calendar: {
                  top: 80,
                  left: 70,
                  right: 70,
                  bottom: 90,
                  cellSize: ["auto", "auto"],
                  range: that.year,
                  splitLine: {
                    lineStyle: {
                      color: "#19ECFF",
                    },
                  },
                  itemStyle: {
                    normal: {
                      color: "rgba(255,255,255,0)",
                      borderColor: "rgba(255,255,255,0)",
                      borderWidth: 0.1,
                    },
                  },
                  monthLabel: {
                    nameMap: "cn",
                    color: "#19ECFF",
                    fontSize: 20,
                    margin: 20,
                  },
                  dayLabel: {
                    firstDay: 0, // 从周日开始
                    nameMap: "cn",
                    color: "#19ECFF",
                    fontSize: 20,
                  },
                  yearLabel: { show: false },
                },
                series: {
                  type: "heatmap",
                  coordinateSystem: "calendar",
                  data: datas,
                },
              };
              that.calendar.setOption(option);
            });
        });
    },
  },
};
</script>