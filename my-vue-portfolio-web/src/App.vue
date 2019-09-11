<template>
  <div class="abput-card">
    <div class="card-title">
      <img src="https://listimg.pinclipart.com/picdir/s/398-3983592_nomnom-sticker-we-bare-bears-png-clipart.png" alt="avatar" class="avatar">
      <div class ="title-text-content">
        <p>About Me</p>
        <h2>John Doe</h2>
      </div>
    </div>
    <div class="card-content"></div>
    <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Dolor sed viverra ipsum nunc aliquet bibendum enim. In massa tempor nec feugiat. Nunc aliquet bibendum enim facilisis gravida. Nisl nunc mi ipsum faucibus vitae aliquet nec ullamcorper. Amet luctus venenatis lectus magna fringilla. Volutpat maecenas volutpat blandit aliquam etiam erat velit scelerisque in. Egestas egestas fringilla phasellus faucibus scelerisque eleifend. Sagittis orci a scelerisque purus semper eget duis. Nulla pharetra diam sit amet nisl suscipit. Sed adipiscing diam donec adipiscing tristique risus nec feugiat in. Fusce ut placerat orci nulla. Pharetra vel turpis nunc eget lorem dolor. Tristique senectus et netus et malesuada.</p>
  </div>
</template>

<style scoped>
.about-card {
   background: #33aac1;
   padding: 3em;
   border-radius: 10px;
   color: white;
   .card-title {
      display: flex;
      text-align: center;
      background: pink;
      border-radius: 10px;
      .avatar {
         border: 1px solid #4aabc2;
         border-radius: 50%;
         margin: 0 30px;
      }
   }
   title-text-content p {
      margin-bottom: 0
      color: #fee12a
   }
   title-text-content h2 {
      margin-top: 0
   }
}

.card-content p {
   line-height: 1.5
   margin: 30px auto
}
</style>
