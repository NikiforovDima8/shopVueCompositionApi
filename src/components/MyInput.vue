<template>
      <input class="input_header" type="text" placeholder="Search" />
</template>


<style>
.input_header {
  width: 300px;
  height: 43px;
  box-shadow: 0px 5px 5px 0px rgba(0, 0, 0, 0.5);
  border-radius: 5px;
  margin-top: 5px;
  margin-bottom: 10px;
  font-size: 16px;
  line-height: 1.5;
  color: #212529;
  background-color: #fff;
  background-clip: padding-box;
  border: 1px solid #bdbdbd;
  border-radius: 0.25rem;
  transition: border-color 0.15s ease-in-out, box-shadow 0.15s ease-in-out;
}

.input_header::placeholder {
  color: #212529;
  opacity: 0.4;
}
.input_header:focus {
  color: #212529;
  background-color: #fff;
  border-color: #bdbdbd;
  outline: 0;
  box-shadow: 0 0 0 0.2rem rgba(158, 158, 158, 0.25);
}
</style>