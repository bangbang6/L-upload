## props

```js
 props: {
    uploadAction: {
      type: String,
      default: '/uploadfile'
    },
    checkFileAction: {
      type: String,
      default: '/checkFile'
    },
    mergeAction: {
      type: String,
      default: '/merge'
    },
    showHashProcess: {
      type: Boolean,
      default: true
    },
    showCubeProcess: {
      type: Boolean,
      default: true
    },
    hashType: {
      type: Number,
      default: 3 //何种方式计算hash
    },
    typeLimit: {
      type: Boolean,
      default: false //限制文件类型
    },
    isCancel: {
      type: Boolean,
      default: true  //是否可以暂停上传
    },
    errorLimit: {
      type: Number,
      default: 3 //错误次数限制
    },
    paralleLimit: {
      type: Number,
      default: 4 //并发数
    }

  },
```

