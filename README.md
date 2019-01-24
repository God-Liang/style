# style
input默认样式
/**
* 背景透明
*/
input {
  background-color: transparent;
  -webkit-text-fill-color: #fff;
}
input:focus {
  background: transparent;
}
input:-webkit-autofill {
  -webkit-animation: autofill-fix 1s infinite;
}
@-webkit-keyframes autofill-fix {
  from {
    background-color: transparent;
  }
  to {
    background-color: transparent;
  }
}
/**
* 背景白色
*/
