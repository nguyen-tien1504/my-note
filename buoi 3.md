# Positioning
là thuộc tính xác định loại của phương pháp định vị vị trí cho thành phần. có 5 giá trị
- Static (default): ko bị ảnh hưởng bởi các thuộc tính top, right, bottom, left. Nó sẽ theo normal flow của page
- Relative: thay đổi vị trí element theo vị trí ban đầu của nó bằng top, right, left, bottom
- Absolute: vị trí tuyệt đối vào thẻ cha.
	- Nếu element nào đc đặt Absolute thì Element đó sẽ đc coi như là bị xóa và Element sau sẽ đc lên vị trí ban đầu
	- Vị trí của một element Absolute sẽ tương quan với vị trí của cha nó nếu thẻ cha được khai báo position khác ngoài Static
- Fixed: vị trí của nó đc CỐ ĐỊNH so với thẻ html . Vị trí ko hề thay đổi. Có thể set thuộc tính top, left, right, bottom nhưng sẽ theo thẻ body 
 ```html
 body{

    padding-top: 60px;

}
```
- Sticky
# Flexbox
Main axis (trục ngang) đi với justify-content
Cross axis (trục dọc) đi với align-items