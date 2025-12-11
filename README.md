<div align="center">
  <img src="https://media.giphy.com/media/v1.Y2lkPTc5MGI3NjExODRiZMmIyZMmIyZMmIyZMmIyZMmIyZMmIyZMmIy/xT0xeuOy2Fcl9vDGiA/giphy.gif" width="100px"/>
  
  <h1>🐾 Hi there, I'm Trần Tuấn Khoa!</h1>
  
  <a href="https://git.io/typing-svg">
    <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&pause=1000&color=20C20E&background=00000000&center=true&vCenter=true&width=435&lines=Python+Backend+Developer+%F0%9F%90%8D;ERP+System+Architect+%F0%9F%8F%AD;System+Optimization+%E2%9A%99%EF%B8%8F" alt="Typing Effect" />
  </a>

  <p>
    <a href="mailto:trantuankhoabc@gmail.com">
      <img src="https://img.shields.io/badge/Email-trantuankhoabc%40gmail.com-d14836?style=flat-square&logo=gmail&logoColor=white" alt="Email" />
    </a>
    <a href="https://www.linkedin.com/in/trantuankhoabc/">
      <img src="https://img.shields.io/badge/LinkedIn-trantuankhoabc-0077B5?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn" />
    </a>
    <a href="https://github.com/trantuankhoabc">
      <img src="https://img.shields.io/badge/GitHub-trantuankhoabc-181717?style=flat-square&logo=github&logoColor=white" alt="GitHub" />
    </a>
    <a href="tel:+84974306100">
      <img src="https://img.shields.io/badge/Phone-(%2B84)%20974306100-25D366?style=flat-square&logo=whatsapp&logoColor=white" alt="Phone" />
    </a>
  </p>
  
  <img src="https://komarev.com/ghpvc/?username=trantuankhoabc&label=Profile%20Views&color=blue&style=flat" alt="Profile Views" />
</div>

---

### 🐾 About Me

<table>
  <tr>
    <td width="60%" valign="top">
      <br>
      <blockquote>
        "Xây dựng hệ thống quản lý sản xuất tối ưu và hiệu quả."
      </blockquote>
      <br>
      <ul>
        <li>📍 <b>Location:</b> Tân Nhựt, Hồ Chí Minh, Việt Nam</li>
        <li>🎂 <b>DOB:</b> 26/04/1995</li>
        <li>🔭 <b>Current Focus:</b> ERP Manufacturing, Business Logic & Database Design</li>
        <li>🌱 <b>Learning:</b> Microservices & Cloud Architecture</li>
        <li>👯 <b>Open for collaboration on:</b> ERP Systems, Python Backend</li>
      </ul>
    </td>
    <td width="40%" align="center">
      <img src="https://i.pinimg.com/originals/e4/26/70/e426702edf874b181aced1e2fa5c6cde.gif" width="100%"/>
    </td>
  </tr>
</table>

### 🐾 Featured Projects

| Project Name | Description | Link |
| :--- | :--- | :---: |
| **ERP Manufacturing** | Hệ thống quản lý quy trình sản xuất, kho bãi và chuỗi cung ứng. Tối ưu hóa luồng dữ liệu doanh nghiệp. | 🏭 _In Progress_ |
| **KUtils Pro** | Bộ công cụ tiện ích hỗ trợ xử lý dữ liệu và tính toán nhanh cho nhà phát triển. | [![Visit](https://img.shields.io/badge/Visit-Site-blue?style=for-the-badge&logo=netlify)](https://kutils-pro.netlify.app/) |

---

### 🐾 Tech Stack & Tools

<div align="center">

| **Core Stack** | **Frontend & Others** | **DevOps & Tools** |
| :---: | :---: | :---: |
| <img src="https://skillicons.dev/icons?i=python,django,flask,postgres" /> | <img src="https://skillicons.dev/icons?i=js,ts,vue,nodejs" /> | <img src="https://skillicons.dev/icons?i=docker,git,postman,vscode,pycharm" /> |
| *Python, Django, Flask, PostgreSQL* | *JS, TS, VueJS, NodeJS* | *Docker, Git, Postman, IDEs* |

</div>

<br>

### 🐾 My Typical ERP Architecture

Mô hình kiến trúc Backend tiêu chuẩn tôi áp dụng cho các hệ thống ERP hiệu suất cao:

```mermaid
graph LR
    User(Client / Frontend) -->|REST API| API_GW[API Gateway / Nginx]
    API_GW -->|Load Balance| App_Service[Python/Django Service]
    App_Service -->|Read/Write| DB[(PostgreSQL)]
    App_Service -->|Cache| Redis[(Redis Cache)]
    App_Service -->|Async Tasks| Celery[Celery Worker]
    Celery -->|Broker| RabbitMQ[RabbitMQ]
    
    %% Styling
    style User fill:#f9f,stroke:#333,stroke-width:2px
    style App_Service fill:#bbf,stroke:#333,stroke-width:2px
    style DB fill:#bfb,stroke:#333,stroke-width:2px
    style Redis fill:#ff9,stroke:#333,stroke-width:2px
