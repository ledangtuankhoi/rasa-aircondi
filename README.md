# Rasa Chatbot Project

## Overview
This project is a Rasa-powered chatbot designed to handle natural language processing (NLP) tasks efficiently. The bot is trained with customized **NLU (Natural Language Understanding)** and **Domain** files in Vietnamese.

## Features
- Customizable intent recognition and entity extraction
- Flexible conversation management with **stories** and **rules**
- Support for **custom actions**
- Easy model training and testing

## Installation
### Prerequisites
Ensure you have the following installed:
- Python 3.8+ (Recommended: Use **pyenv** for managing Python versions)
- Rasa
- Virtual environment management tool (e.g., `venv` or `pyenv-virtualenv`)

### Setup Steps
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/rasa-project.git
   cd rasa-project
   ```
2. Create a virtual environment and activate it:
   ```bash
   python -m venv rasa_env
   source rasa_env/bin/activate  # On Windows: rasa_env\Scripts\activate
   ```
3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
4. Train the model:
   ```bash
   rasa train
   ```
5. Run the chatbot:
   ```bash
   rasa shell
   ```

## Model Training
To ensure high-quality training data:
- Use **diverse NLU examples**
- Define **clear and structured intents**
- Optimize **stories** for better dialog flow
- Validate the domain configuration

### Automated Testing
To automate testing:
```bash
rasa test
```
This will evaluate the model and provide test reports.

## Custom Actions
If your bot requires custom actions, run the action server:
```bash
rasa run actions
```

## Deployment
For production, consider deploying using **Docker, Kubernetes**, or **cloud services** like **Rasa X**.

## Contributors
Feel free to contribute! Fork the repo, create a branch, and submit a PR.

---

# Dự Án Chatbot Rasa

## Tổng Quan
Dự án này là một chatbot sử dụng **Rasa** để xử lý ngôn ngữ tự nhiên (**NLP**) hiệu quả. Bot đã được huấn luyện với các tệp **NLU** và **Domain** bằng tiếng Việt.

## Tính Năng
- Nhận diện ý định và trích xuất thực thể tùy chỉnh
- Quản lý hội thoại linh hoạt với **stories** và **rules**
- Hỗ trợ **hành động tùy chỉnh**
- Dễ dàng huấn luyện và kiểm thử mô hình

## Cài Đặt
### Yêu Cầu
Bạn cần cài đặt:
- Python 3.8+ (Nên sử dụng **pyenv** để quản lý phiên bản Python)
- Rasa
- Công cụ quản lý môi trường ảo (e.g., `venv` hoặc `pyenv-virtualenv`)

### Các Bước Thiết Lập
1. Clone repository:
   ```bash
   git clone https://github.com/yourusername/rasa-project.git
   cd rasa-project
   ```
2. Tạo và kích hoạt môi trường ảo:
   ```bash
   python -m venv rasa_env
   source rasa_env/bin/activate  # Trên Windows: rasa_env\Scripts\activate
   ```
3. Cài đặt dependencies:
   ```bash
   pip install -r requirements.txt
   ```
4. Huấn luyện mô hình:
   ```bash
   rasa train
   ```
5. Chạy chatbot:
   ```bash
   rasa shell
   ```

## Huấn Luyện Mô Hình
Để đảm bảo dữ liệu huấn luyện chất lượng:
- Cung cấp **nhiều ví dụ NLU đa dạng**
- Định nghĩa **ý định rõ ràng và có cấu trúc**
- Tối ưu hóa **stories** để điều hướng hội thoại tốt hơn
- Kiểm tra kỹ tệp cấu hình domain

### Kiểm Tra Tự Động
Chạy lệnh sau để kiểm thử mô hình:
```bash
rasa test
```
Lệnh này sẽ đánh giá mô hình và cung cấp báo cáo kiểm thử.

## Hành Động Tùy Chỉnh
Nếu bot cần sử dụng **custom actions**, hãy chạy server action:
```bash
rasa run actions
```

## Triển Khai
Đối với môi trường production, bạn có thể triển khai bằng **Docker, Kubernetes**, hoặc sử dụng **Rasa X**.

## Đóng Góp
Hãy tham gia đóng góp! Fork repo, tạo branch mới, và gửi **Pull Request**.

---

🚀 **Happy Coding!**

