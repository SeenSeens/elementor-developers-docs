# Best Practices

<Badge type="tip" vertical="top" text="Elementor Core" /> <Badge type="warning" vertical="top" text="Basic" />

Hướng dẫn về Thực hành Tốt nhất này là một tài liệu sống dành cho các nhà phát triển addon Elementor, có nghĩa là được sửa đổi khi Elementor thực hiện các thay đổi, giới thiệu các tính năng mới và cung cấp các đề xuất bổ sung. Chúng tôi khuyên bạn nên làm theo các thực hành tốt nhất này.

## Supported PHP Versions

Đảm bảo addon của bạn tương thích với phiên bản PHP được sử dụng nhiều nhất (v7.4) và các phiên bản PHP mới nhất (v8.0 trở lên).

## Compatibility Tag

Elementor có riêng của nó [header comments](https://developers.elementor.com/docs/addons/plugin-header/) nơi bạn có thể lưu ý phiên bản Elementor mà addon đã được thử nghiệm. Đây là một tiêu đề tùy chọn, nhưng chúng tôi khuyên bạn nên sử dụng nó.

## Compatibility Checks

[Check which Elementor and PHP versions](https://developers.elementor.com/docs/addons/compatibility/) trang web sử dụng để đảm bảo addon của bạn hỗ trợ nó. Nếu không, hãy thông báo cho người dùng rằng trang web không đáp ứng các yêu cầu của addon.

## Scripts & Style Registration

Elementor có cách riêng để [register scripts and styles](https://developers.elementor.com/docs/scripts-styles/). Sử dụng các phương pháp được đề xuất sẽ đảm bảo addon của bạn được tối ưu hóa về hiệu suất.

## Internationalization

Sử dụng chức năng WordPress để [quốc tế hóa](https://developer.wordpress.org/apis/internationalization/internationalization-functions/) chuỗi của bạn.

## Remove Deprecated Code

Đã có addon? Chạy nó thông qua  [Elementor Deprecated Code Detector](https://github.com/matipojo/elementor-deprecated-code-detector) để xem addon của bạn có chứa bất kỳ [deprecated code](https://developers.elementor.com/docs/deprecations). Nếu vậy, chúng tôi thực sự khuyên bạn nên xóa nó.

## Adopt Latest Performance Features

Triển khai [Element Caching](https://developers.elementor.com/elementor-3-22-developers-update/) để lưu trữ dữ liệu đầu ra trong bộ nhớ cache để các trang web hoạt động hiệu quả hơn.

## Elementor Pro Developer License

Kiểm tra với Elementor Pro bằng cách yêu cầu [Developer License](https://elementor.com/pages/addon-developers-corner/).

## Security

Tham gia vào Patchstack miễn phí [mVDP Program](https://elemn.to/patchstack-for-plugins) để duy trì tính bảo mật cho sản phẩm của bạn bằng cấu trúc báo cáo lỗ hổng rõ ràng.
