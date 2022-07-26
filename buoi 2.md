## Kết hợp CSS 2 element
```html
h2,

h3 {

  font-weight: 500;

  line-height: 1.2;

  text-transform: capitalize;

}
```

## Sự khác nhau giữa div > h3 và div h3
div > h3 là áp dụng cho con TRỰC TIẾP của thẻ div
div h3 là áp dụng cho tất cả h3 kể cả trng 1 thẻ khác trong thẻ div
https://www.w3schools.com/cssref/css_selectors.asp

## nth trong nth-child() CSS là chọn vị trí thứ n
tr:first-child / tr:last-child | Chọn tr đầu tiên / cuối cùng của table 
tr:nth-child(odd) / tr:nth-child(even) | Chọn tr lẻ / chẵn của table 
tr:nth-child(10n-1) | Chọn các tr có số thứ tự 9, 19, 29 ... 
tr:nth-child(-n+6) | Chọn 6 tr đầu tiên của table
https://codevivu.com/front-end/cong-dung-huu-ich-tu-nth-childn-trong-css/

## Thứ tự độ ưu tiên style trong CSS
css bình thường < class < id < inline < !important
## Sự khác nhau giữa Block Element và Inline
https://thietke.website/hoc-viet-code-web/css/kien-thuc-co-ban-css-inline-vs-block-vs-inline-block/


