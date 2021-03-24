# noxoncoaching

## Итерация 1
Форма отправки фантика и доступ к ней по токену
1.2. добавил скрипт проверки web3 (кажется, нужен родной код Метамаска, но не понимаю, как подключить)
```js
<script type="text/javascript">
  window.addEventListener('load', function() {
  if (typeof web3 !== 'undefined') {
  console.log('web3 is enabled')
  if (web3.currentProvider.isMetaMask === true) {
    console.log('MetaMask is active')
  } else {
    console.log('MetaMask is not available')
  }
  } else {
    console.log('web3 is not found')
  }
})
</script>
```

![Uploading Screen Shot 2021-03-24 at 17.18.19.png…]()

1.1. заебенил две странички: 503 и шаблон формы отправки

![Screen Shot 2021-03-24 at 16 03 01](https://user-images.githubusercontent.com/9741823/112316940-9ebf2780-8cbc-11eb-92ba-eae26a7e88f2.png)
