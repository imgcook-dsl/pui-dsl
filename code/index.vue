<template>
  <div class="mod">
    <div class="box">
      <div class="layerWrap">
        <img
          class="layer"
          src="https://ai-sample.oss-cn-hangzhou.aliyuncs.com/test/ee24b05048e311eba06faf2750a828ad.png"
        />
        <div class="bgWrap">
          <img
            class="bg"
            src="https://ai-sample.oss-cn-hangzhou.aliyuncs.com/test/ee24b05048e311eba06faf2750a828ad.png"
          />
          <div class="backgroundWrap">
            <img
              class="background"
              src="https://ai-sample.oss-cn-hangzhou.aliyuncs.com/test/ee70113048e311eba7aea5a724f174e6.png"
            />
            <img
              class="icon"
              src="https://img.alicdn.com/imgextra/i1/O1CN01vMdNKr1LZr4vomWaQ_!!6000000001314-2-tps-28-24.png"
            />
            <img
              class="icon_1"
              src="https://img.alicdn.com/imgextra/i1/O1CN01Aqg5qU1FC8sScYHSY_!!6000000000450-2-tps-50-28.png"
            />
            <img
              class="icon_2"
              src="https://ai-sample.oss-cn-hangzhou.aliyuncs.com/test/f1efe92048e311eb926ced97ee3bf1f2.png"
            />
          </div>
          <span class="txt">剩余可用(元)</span>
          <span class="word">43,001.21</span>
          <div class="block">
            <span class="text">已消费额度</span>
            <span class="txt_1">6,999.79</span> <span class="word_1">明细</span>
          </div>
          <poppy-icon name="arrow_up" />
        </div>
      </div>
      <div class="block_1">
        <poppy-tab
          inline
          v-model="selected1"
          :data="listwithTwoValue"
        ></poppy-tab>
        <div class="block_2">
          <span class="word_2">剩余待还(元)</span>
          <div class="normal_component_2">
            <div class="block_3">
              <img
                class="icon_4"
                src="https://ai-sample.oss-cn-hangzhou.aliyuncs.com/test/eec5f96048e311eb85da4b2ebc278f1b.png"
              />
            </div>
          </div>
        </div>
        <span class="text_2">5,612.09</span>
        <div class="group_1">
          <poppy-button type="plain">次要操作Normal</poppy-button
          ><poppy-button type="primary">主要操作Normal</poppy-button>
        </div>
      </div>
      <div class="hd">
        <img
          class="icon_5"
          src="https://ai-sample.oss-cn-hangzhou.aliyuncs.com/test/edfdc76048e311ebafc4fbc6359211cd.png"
        />
        <div class="container">
          <img
            class="icon_6"
            src="https://ai-sample.oss-cn-hangzhou.aliyuncs.com/test/edd9768048e311eb9ca505649a2b3fc7.png"
          />
          <img
            class="icon_7"
            src="https://ai-sample.oss-cn-hangzhou.aliyuncs.com/test/edae6ee048e311eba0a48f3d4a09c34e.png"
          />
          <div class="container_1"><div class="color_1" /></div>
          <img
            class="dot"
            src="https://ai-sample.oss-cn-hangzhou.aliyuncs.com/test/ed8b568048e311eba14c9fe98bab92a9.png"
          />
        </div>
      </div>
      <div class="bd">
        <div class="block_4">
          <img
            class="icon_8"
            src="https://ai-sample.oss-cn-hangzhou.aliyuncs.com/test/ed672cb048e311ebbe940f5397e98217.png"
          />
        </div>
        <span class="text_3">我的账单</span>
      </div>
      <div class="submain">
        <div class="normal_component_5">
          <div class="outer">
            <img
              class="icon_9"
              src="https://img.alicdn.com/imgextra/i4/O1CN01XLvvWD1iU7HRK0w6x_!!6000000004415-2-tps-44-52.png"
            />
          </div>
          <div class="block_5">
            <span class="txt_5">我的分期</span>
            <span class="word_3">4笔进行中</span>
          </div>
        </div>
        <div class="group_2">
          <div class="group_3">
            <img
              class="icon_10"
              src="https://img.alicdn.com/imgextra/i2/O1CN01jjnSh124Ao85LYW7S_!!6000000007351-2-tps-48-52.png"
            />
            <div class="colorDiv_1" />
          </div>
          <div class="container_2">
            <span class="text_4">我的账单</span>
            <span class="txt_6">查看明细</span>
          </div>
        </div>
      </div>
      <div class="row">
        <img
          class="actionBg"
          src="https://ai-sample.oss-cn-hangzhou.aliyuncs.com/test/ef76f9e048e311ebad2369729f2135fb.png"
        />
      </div>
      <div class="main">
        <div class="container_3">
          <div class="color_2" />
          <div class="colorDiv_2" />
        </div>
        <div class="container_4">
          <div class="color_3" />
          <div class="colorDiv_3" />
        </div>
        <div class="container_5">
          <div class="color_4" />
          <div class="colorDiv_4" />
        </div>
        <div class="container_6">
          <div class="color_5" />
          <div class="colorDiv_5" />
        </div>
        <div class="buttonWrap"><span class="button">Max花轻松付</span></div>
        <div class="container_7">
          <div class="color_6" />
          <div class="colorDiv_6" />
        </div>
        <div class="container_8">
          <div class="color_7" />
          <div class="colorDiv_7" />
        </div>
        <div class="container_9">
          <div class="color_8" />
          <div class="colorDiv_8" />
        </div>
        <div class="container_10">
          <div class="color_9" />
          <div class="colorDiv_9" />
        </div>
      </div>
      <div class="row1">
        <div class="container_11">
          <img
            class="largeIcon"
            src="https://ai-sample.oss-cn-hangzhou.aliyuncs.com/test/efa9548048e311eb926ced97ee3bf1f2.png"
          />
          <div class="outer_1">
            <span class="text_5">电子账户</span>
            <span class="info">无卡支付 享受便捷</span>
          </div>
          <div class="block_6">
            <img
              class="mark"
              src="https://ai-sample.oss-cn-hangzhou.aliyuncs.com/test/efd0648048e311eb84dc3be6ed3f154d.png"
            />
            <img
              class="label"
              src="https://ai-sample.oss-cn-hangzhou.aliyuncs.com/test/effa81c048e311ebbc7391a47665341a.png"
            />
          </div>
        </div>
        <div class="block_7">
          <span class="word_4">多场景消费</span>
          <div class="group_4">
            <img
              class="largeIcon_1"
              src="https://ai-sample.oss-cn-hangzhou.aliyuncs.com/test/f020323048e311ebb0628f148c34f018.png"
            />
            <div class="group_5">
              <img
                class="largeIcon_2"
                src="https://ai-sample.oss-cn-hangzhou.aliyuncs.com/test/f041eb0048e311eba418f752602f0f2a.png"
              />
              <img
                class="largeIcon_3"
                src="https://ai-sample.oss-cn-hangzhou.aliyuncs.com/test/f06a81a048e311ebaa01bf1c9fb70e8a.png"
              />
            </div>
          </div>
          <span class="info_1">线上线下 随用随还</span>
        </div>
      </div>
      <div class="ft"><div class="color_10" /></div>
    </div>
  </div>
</template>
<script>
export default {
  data() {
    return {
      constants: {}
    };
  },
  methods: {}
};
</script>
<style src="./index.response.css" />
