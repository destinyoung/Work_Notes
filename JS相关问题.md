##### JSON.stringify()
      - 用于打印对象

##### 当数组为空时，打印的值为空，但是判断时却不为空
      - console.log("数据类型"+Object.prototype.toString.call(vm.results)) ;    //数据类型[object Array]
      - console.log("数组长度"+vm.results.length)   //数组长度0
      - console.log("results"+vm.results)  // results
