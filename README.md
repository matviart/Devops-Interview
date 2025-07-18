# Devops-Interview
Interview
<details> <summary><b>1. Простой: Как посмотреть активные процессы? ▶️</b></summary>
top        # Интерактивный мониторинг  
htop       # Улучшенный top (установить: sudo apt install htop)  
ps aux     # Статичный список процессов  

</details><details> <summary><b>2. Средний: Как найти все файлы .log измененные за последние 7 дней? ▶️</b></summary>
find / -name "*.log" -mtime -7
