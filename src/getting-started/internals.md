# Nội dung Elementor

<Badge type="tip" vertical="top" text="Elementor Core" /> <Badge type="warning" vertical="top" text="Basic" />

Elementor có công nghệ cơ bản mà chúng tôi gọi là internals. Trong phần này, chúng tôi sẽ giới thiệu cho bạn các khái niệm bạn cần hiểu khi phát triển các addon Elementor của mình.

## Available Internals

Dưới đây là danh sách các thành phần bên trong Elementor cùng với mô tả ngắn và liên kết đến thông tin chuyên sâu hơn:

* [The Editor](./../editor/)

Trình chỉnh sửa là nơi người dùng tạo trang và kiểm soát cài đặt của họ. Nó được chia thành các khu vực xem trước và bảng điều khiển. Bảng điều khiển lưu trữ danh sách các widget và là nơi người dùng kiểm soát các cài đặt. Màn hình xem trước là nơi họ thấy trang sẽ trông như thế nào.

* [Managers](./../managers/)

Kiến trúc của Elementor đăng ký và hủy đăng ký các phần tử bằng cách sử dụng các trình quản lý đặc biệt. Các nhà phát triển bên ngoài cần sử dụng các trình quản lý này để đăng ký các phần tử của riêng họ. Điều này sẽ cho Elementor biết về chúng, cho phép chúng sử dụng.

* [Scripts & Styles](./../scripts-styles/)

Các nhà phát triển cần biết cách các thành phần Elementor khác nhau tải các tệp JS và CSS tùy chỉnh. Vì các tệp này có thể ảnh hưởng nghiêm trọng đến hiệu suất, điều quan trọng là phải tìm hiểu các phương pháp thích hợp để tải chúng cho từng thành phần.

* [Hooks](./../hooks/)

Có nhiều loại hook có thể sử dụng với Elementor. Tài liệu này chứa danh sách đầy đủ toàn bộ các hook có sẵn mà Elementor cung cấp - filter hooks, action hooks, PHP hooks, JS hooks, frontend hooks and editor hooks.

* [Deprecations](./../deprecations/)

Theo thời gian, mã sẽ bị xóa hoặc thay thế. Quá trình ngừng sử dụng diễn ra dần dần và quá trình ngừng sử dụng Elementor bao gồm một số bước. Các nhà phát triển cần biết cách Elementor ngừng sử dụng mã và cách họ cần gỡ lỗi và cập nhật mã đã ngừng sử dụng.

* [CLI](./../cli/)

Elementor tích hợp với WP-CLI, cho phép các nhà phát triển chạy một số tác vụ Elementor thông qua giao diện dòng lệnh mà không cần sử dụng trình duyệt web. Tất cả các lệnh có sẵn cùng với các đối số và ví dụ sử dụng của chúng đều được liệt kê ở đây.

* [Building Addons](./../addons/)

Phần này chứa thông tin dành riêng cho những người không quen thuộc với WordPress. Phần thảo luận này về cơ sở phát triển plugin WordPress, cũng như các tiện ích bổ sung Elementor và các chủ đề nâng cao, bao gồm thông tin cơ bản về plugin và lập trình hướng đối tượng.
