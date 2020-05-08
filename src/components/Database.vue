<template>
  <div class="signin" style="width:500px">
    <div class="items-center">
      <div class="col-md-4">アカウント名</div>
      <div class="col-md-3">
        <input type="text" placeholder="Username" v-model="username" />
      </div>
    </div>
    <div class="items-center">
      <div class="col-md-4">パスワード</div>
      <div class="col-md-3">
        <input type="password" placeholder="Password" v-model="password" />
      </div>
    </div>
    <div class="items-center">
      <div class="col-md-12">
        <button class="btn btn-primary" @click="signIn">サインイン</button>
      </div>
    </div>
  </div>
</template>

<style scoped>
input {
  margin: 10px 0;
  padding: 10px;
}
</style>
