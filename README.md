# Unclosed Span Tag in HTML

This repository demonstrates a simple HTML error involving an unclosed `<span>` tag. While not as common as other HTML errors, this issue can lead to unexpected rendering behaviors.

## Bug Description
The last paragraph contains a `<span>` tag with styling (`font-weight: bold;`) that is not closed using the closing tag `</span>`. This missing closing tag can cause the bold styling to leak into subsequent elements, resulting in unexpected formatting or rendering issues in the browser.