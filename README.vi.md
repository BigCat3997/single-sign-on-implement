# Làm thế nào để triển khai single-sign-on

## Định nghĩa

SSO giúp người dùng chỉ cần đăng nhập một lần mà có thể sử dụng hàng loạt nhiều ứng dụng có liên quan nhau mà không cần phải đăng nhập lại. 

[for-more-references](https://en.wikipedia.org/wiki/Single_sign-on)


Một ví dụ điển hình cho việc sử dụng hằng ngày, cũng là hệ thống có hỗ trợ SSO đầu tiên mà tác giả biết đến

Đó chính là thao tác với những dịch vụ của Google. Việc bạn chỉ cần đăng nhập vào bất cứ 1 hệ thống nào của Goole (Ví dụ như Gmail) và sau đó bạn đã có thể sử dụng các ứng dụng khác của họ mà không cần phải đăng nhập như Youtube, Google Map, Goole Translate, Google abc, Goole xyz...

Nếu vẫn chưa hiểu, đây là một ví dụ cho việc triển khai SSO cho doanh nghiệp

Công ty F triển khai nhiều ứng dụng A, B, C, D cho hệ thống của họ. Họ quyết định xây dựng 1 ứng dụng E giành cho việc xác thực khi người dùng sử dụng ứng dụng A, B, C, D bắt buộc phải gọi tới E để thực hiện việc đăng nhập. Và nếu cùng 1 người dùng cần tương tác với cả 4 ứng dụng A, B, C, D trên thì việc đăng nhập tận 4 lần là một điều bất tiện. Từ đó khái niệm Sign-Singl-On (SSO) ra đời để giúp thao tác đăng nhập này được tiện lợi hơn, nghĩa là bạn chỉ cần đăng nhập vào ứng dụng A và không cần phải lặp lại thao tác này cho 3 ứng dụng còn lại.

> Trên lý thuyết, SSO chỉ là một khái niệm, một ý tưởng bạn cần phải có đủ kiến thức về các công nghệ của http, policy để triển khai nó cho hệ thống của mình.

