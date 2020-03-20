# eureka-server

- `cd ${project_dir}`
- `maven clean package`
- `docker build -t landykingdom/eureka-server:0.0.1 .`
- `docker run -p 8761:8761 -d landykingdom/eureka-server:0.0.1` or `docker run -p 8761:8761 -v /${your_config_file}:/app/application.yml -d landykingdom/eureka-server:0.0.1`
- Open `http://localhost:8761` in browser.
