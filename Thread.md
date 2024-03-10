(4 nhân 8 luồng vs 6 nhân 6 luồng) Số thread xử lý = Số core, 1 nhân 2 luồng tức là 1 nhân nhận tập lệnh của 2 OS thread 1 lúc -> khi gặp sự kiện cache missing trên 1 OS thread -> để tránh CPU idle, CPU chuyển sang OS thread còn lại để xử lý tiếp
![[Pasted image 20240306092937.png]]
Mapping N-1 with OS Thread