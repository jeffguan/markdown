# Markdown
## 添加代码   
       let data = try! NSData(contentsOf: url! as URL, options: NSData.ReadingOptions())
          let json = try! JSONSerialization.jsonObject(with: data as Data, options:JSONSerialization.ReadingOptions.allowFragments) as! NSDictionary
        let aResult  = results[0] as! NSDictionary
        let location = aResult["location"] as! NSDictionary
        debugPrint(location)
        let country = location["country"] as! String
  
##链接
这是一个百度的链接[打开链接](http://baidu.com)

##图片插入
![GitHub set up](http://img.sc115.com/uploads1/sc/jpgs/1508/fpic6092_sc115.com.jpg)



