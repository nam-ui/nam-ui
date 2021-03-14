# 1. Cài đặt phần mềm https://nodejs.org/en/
    - nodeJS (là 1 thư viện của javascrit)
    - npm (Phần mềm quản lý toàn bộ thư viện của JS)
        - Global : Cài đặt thư viện cho cả máy 
        - Local: cài đặt thư viện cho chính Project đang đứng
     - kiểm tra
            - node --version
            - npm --version
# 2. Cài đặt thư viện co reacJS 
https://www.npmjs.com/package/npx
    - npm i npx 
        - npx thư viện để cài đặt khởi tạo ứng đạng REAC
        - npm i -g npx 
        - npm --install --global  npx 

# 3. Init project
    - npx create-react-app ohana --template typescript
    cd + Tên ProJect  (tab)
    npm start 
# 5. cấu trúc thư mục
    - node_modules Chứa toàn bộ thư viện của project
    - src chứa toàn bộ soure code của Project
    - package json
        - Quản lý thư viện
        - Cấu hình scrit
# 6. Cài đặt hổ trợ React Trên Visual Studio code
    - Reactjs code snippets
    - Gỏ rcc để tạo template reactjs
# 7. router
    - npm install react-router-dom
    - https://reactrouter.com/web/guides/quick-start
# 8. Giao tiếp giửa các combonent
    - Props là đầu vào của component
    - Định nghỉa kiểu dữ liệu cho pros bằng syntax type Props = {}
    - Đưa kiểu dử liệu đầu vào cho component <Props,{}>
    
npm i axios
