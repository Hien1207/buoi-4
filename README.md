# buoi-4
Nội dung bài học buổi 4: 

1/ Slot : ứng dụng để đóng gói, chia component
  - Dùng slot trong template của component để viết những html khác nhau giữa các thành phần render của component.
  - Navbar , Header, Footer : giữ nguyên không thay đổi khi chuyển sang component khác.
  - PageContent :thay đổi theo component.
  - Phần code nằm giữa <PageLayout> và </PageLayout> sẽ được tự động đặt vào vị trí mà bạn khai báo <slot/> trong component <PageLayout />. Ngoài ra trong component <PageLayout /> bạn cũng có thể đặt một giá trị mặc định.
  - Name slot: ta có thể tạo ra nhiều slot bằng cách đặt cho chúng một cái tên cố định.
  - Scope slot :cho phép component cha sử dụng đến component con có dùng scope có thể tái sử dụng logic bên trong component con.
2/ Đệ quy component(Tree) : ứng dụng để hiển thị dữ liệu dạng cây, sidebar
   - Quy tắc : data nằm phía trên cây cha
   - Đệ quy component cơ bản:
     1) Duyệt qua mảng, load content các phần tử và qua bước (2)
     2) Sau đó, Trong các phần tử đã load nếu có phần tử con thì thực hiện lại bước (1)
3/ VueCLI :
  - Vue router :router thực chất là định nghĩa cách url để ứng dụng điều hướng tới đúng hàm, đúng component xử lý nó (chuyển đổi component).Vue route có rất nhiều tính năng, ngoài tính năng chính là route thì nó còn hỗ trợ thêm các tính năng đặc trưng của ứng dụng front-end, có thể kể đến như:
           * Hỗ trợ mapping lồng nhau route/view
           * Route params, query, wildcards.
           * Hỗ trợ liên kết với CSS một cách tự động
           * Là một fine-grained Navigation
           * Hỗ trợ tùy chỉnh hành vi Scroll của người dùng.
  - Vuex (state management) :là thư viện giúp quản lý trạng thái các component trong Vue.js, nó là nơi lưu trữ tập trung cho tất cả các component trong một ứng dụng, với nguyên tắc trạng thái chỉ có thể được thay đổi theo kiểu có thể dự đoán.
4/ Install: bootstrap,devtool,VueCLI
