<template>
  <section>
    <h2>イントロ</h2>
    <div id="note-containnaer">
      <div class="note"><div class="hight-tone">レ</div></div>
      <div class="note"><div class="smallh">ド</div></div>
      <div class="note"><div class="big">シ</div></div>
      <div class="note"><div class="small">ソ</div></div>
      <div class="note"><div class="big">レ</div></div>
      <div class="note"><div class="small">ソ</div></div>
      <div class="note"><div class="big">ラ</div></div>
      <div class="note"><div class="small">ソ</div></div>
    </div>

    <div id="note-containnaer">
      <div class="note"><div class="hight-tone">レ</div></div>
      <div class="note"><div class="smallh">ド</div></div>
      <div class="note"><div class="big">シ</div></div>
      <div class="note"><div class="small">ソ</div></div>
      <div class="note"><div class="big">レ</div></div>
      <div class="note"><div class="small">ソ</div></div>
      <div class="note"><div class="big">ラ</div></div>
      <div class="note"><div class="small">シ</div></div>
    </div>

    <div id="note-containnaer">
      <div class="note"><div class="big faB">ファ</div></div>
      <div class="note"><div class="small">ソ</div></div>
      <div class="note"><div class="small">♪</div></div>
      <div class="note"><div class="small">♪</div></div>
      <div class="note"><div class="small">♪</div></div>
      <div class="note"><div class="small">レ</div></div>
      <div class="note"><div class="big">ラ</div></div>
      <div class="note"><div class="small">シ</div></div>
    </div>

    <div id="note-containnaer">
      <div class="note"><div class="big faB">ファ</div></div>
      <div class="note"><div class="bigh faB">ファ</div></div>
      <div class="note"><div class="smallh">♪</div></div>
      <div class="note"><div class="smallh">♪</div></div>
      <div class="note"><div class="smallh">♪</div></div>
      <div class="note"><div class="smallh">♪</div></div>
      <div class="note"><div class="smallh">♪</div></div>
      <div class="note"><div class="smallh">♪</div></div>
    </div>
  </section>
</template>

<script></script>

<style scoped>
body {
  text-align: center;
  justify-content: center;
  color: azure;
}
.note {
  width: 100px;
  height: 100px;
  justify-content: center;
  margin-right: 0;
  display: flex;
  margin-left: 0.5rem;
}
#note-containnaer {
  display: flex;
  text-align: center;
  justify-content: center;
  margin-bottom: 1rem;
}

.hight-tone {
  background-color: rgb(1, 189, 170);
  font-size: 80px;
  width: 100px;
  height: 100px;
  border-radius: 50%;
  color: white;
}
.big {
  font-size: 80px;
  width: 100px;
  height: 100px;
  background-color: rgb(214, 54, 54);
  border-radius: 50%;
  color: white;
  line-height: 6rem;
}
.bigh {
  font-size: 80px;
  width: 100px;
  height: 100px;
  background-color: rgb(1, 189, 170);
  border-radius: 50%;
  color: white;
}

.faB {
  font-size: 50px;
  line-height: 6rem;
}
.faS {
  margin-top: 2rem;
  font-size: 30px;
  width: 60px;
  height: 60px;
  background-color: brown;
  border-radius: 50%;
  color: white;
  justify-content: center;
  text-align: center;
  line-height: 4rem;
}
.small {
  margin-top: 2rem;
  font-size: 50px;
  width: 70px;
  height: 70px;
  background-color: brown;
  border-radius: 50%;
  color: white;
  justify-content: center;
  text-align: center;
  line-height: 4rem;
}
.smallh {
  margin-top: 2rem;
  font-size: 50px;
  width: 70px;
  height: 70px;
  background-color: rgb(1, 189, 170);
  border-radius: 50%;
  color: white;
  justify-content: center;
  text-align: center;
  line-height: 4rem;
}
</style>
