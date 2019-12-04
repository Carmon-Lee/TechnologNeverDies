## JDK 当中的设计模式

## 创建型模式
#### 抽象工厂模式（创建的结果是工厂对象）
- javax.xml.parsers.DocumentBuilderFactory#newInstance()
- javax.xml.transform.TransformerFactory#newInstance()
- javax.xml.xpath.XPathFactory#newInstance()
#### 创建者模式
- java.lang.StringBuilder#append() (unsynchronized)
- java.lang.StringBuffer#append() (synchronized)
- java.nio.ByteBuffer#put() (also on CharBuffer, ShortBuffer, IntBuffer, LongBuffer, FloatBuffer and DoubleBuffer)
- 所有实现了 java.lang.Appendable 接口的类
- java.util.stream.Stream.Builder
#### 工厂模式（创建的结果是普通对象）
- java.util.Calendar#getInstance()
- java.util.ResourceBundle#getBundle()
- java.text.NumberFormat#getInstance()
- va.nio.charset.Charset#forName()
- va.net.URLStreamHandlerFactory#createURLStreamHandler(String) 
- va.util.EnumSet#of()
- vax.xml.bind.JAXBContext#createMarshaller() 
#### 原型模式
- java.lang.Object#clone() (类必须实现 Clonable)
#### 单例模式
- java.lang.Runtime#getRuntime()
- va.awt.Desktop#getDesktop()
- java.lang.System#getSecurityManager()

## 结构性模式



## 行为型模式
#### 责任链模式
多个对象组成一个链，在对象的一个类当中调用另外一个实现了相同接口的类的相同方法
- java.util.logging.Logger#log()
- javax.servlet.Filter#doFilter()


[参考链接](https://stackoverflow.com/questions/1673841/examples-of-gof-design-patterns-in-javas-core-libraries)


