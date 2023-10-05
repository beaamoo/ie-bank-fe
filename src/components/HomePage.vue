<template>
  <div class="homepage">
    <div class="container">
      <div class="row">
        <div class="col-sm-12">
          <h1 class="title">Welcome to IE Bank</h1>
          <div class="button-container">
            <button class="btn btn-primary btn-lg" @click="$router.push('/accounts')">Go to Accounts</button>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<style>
.homepage {
  display: flex;
  justify-content: center;
  align-items: center;
  height: 100vh;
  background-color: #f5f5f5;
}

.title {
  font-size: 3rem;
  margin-bottom: 2rem;
  text-align: center;
}

.button-container {
  display: flex;
  justify-content: center;
  align-items: center;
  height: 100%;
}

.btn {
  display: block;
}
</style>
