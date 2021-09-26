1、通过机场订阅链接导入
Quantumult X 支持SS/SSR订阅链接、支持 Quantumult X 格式的 V2Ray和Trojan订阅链接。
机场网站有 Quantumult X 订阅链接的，直接复制订阅链接到 圈X的引用（订阅）里粘贴，或者点击导入到 Quantumult X 。
机场网站无 Quantumult X 订阅链接的，SS/SSR订阅链接可以使用，如果是V2Ray和Trojan订阅链接不能直接导入 Quantumult X ，
需要添加一个 资源解析器，使用 资源解析器 后，可以将 Quantumult X 不识别的 节点或订阅链接 轻松的导入。
✈️ 如何添加资源解析器？
打开Quantumult X 配置文件，找到 [general] 位置，添加以下代码：
resource_parser_url=https://raw.githubusercontent.com/KOP-XIAO/QuantumultX/master/Scripts/resource-parser.js
