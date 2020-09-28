# VUE-for-java-SM4-encryption-and-decryption
找了市面上所有的vue sm4 算法,发现java 解密不了，所以自己写了一个工具类

### vue使用

```
import { encryptData_ECB, decryptData_ECB } from '@/utils/SM4Utils'

const ciphertext = encryptData_ECB("张三")

console.log(ciphertext)

const data = decryptData_ECB(encryptData_ECB("张三"))

console.log(data)

```
### java使用
[java使用见main方法](https://github.com/Zhao2018Mr/VUE-for-java-SM4-encryption-and-decryption/blob/master/java/entrycption/SM4Utils.java "java使用见main方法")