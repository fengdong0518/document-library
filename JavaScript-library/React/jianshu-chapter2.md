# 仿简书项目 - 2 - 标题没想好
> create by **jsliang** on **2018-9-10 16:17:24**  
> Recently revised in **2018-9-10 16:17:10**

<br>

## 第二章 标题没想好

<br>

### 1.1 创建公共组件

![图](../../public-repertory/img/js-react-jianshu-chapter2-1.png)

1. 新建 `common` 文件夹
2. 新建 `header` 文件夹
3. 新建 `index.js` 文件
> **index.js**
```
import React, { Component } from 'react';

class Header extends Component {
    render() {
        return (
            <div>header</div>
        )
    }
}

export default Header;
```


<br>

> <a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/"><img alt="知识共享许可协议" style="border-width:0" src="https://i.creativecommons.org/l/by-nc-sa/4.0/88x31.png" /></a><br /><span xmlns:dct="http://purl.org/dc/terms/" property="dct:title">jsliang的文档库</span> 由 <a xmlns:cc="http://creativecommons.org/ns#" href="https://github.com/LiangJunrong/document-library" property="cc:attributionName" rel="cc:attributionURL">梁峻荣</a> 采用 <a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/">知识共享 署名-非商业性使用-相同方式共享 4.0 国际 许可协议</a>进行许可。<br />基于<a xmlns:dct="http://purl.org/dc/terms/" href="https://github.com/LiangJunrong/document-library" rel="dct:source">https://github.com/LiangJunrong/document-library</a>上的作品创作。<br />本许可协议授权之外的使用权限可以从 <a xmlns:cc="http://creativecommons.org/ns#" href="https://creativecommons.org/licenses/by-nc-sa/2.5/cn/" rel="cc:morePermissions">https://creativecommons.org/licenses/by-nc-sa/2.5/cn/</a> 处获得。