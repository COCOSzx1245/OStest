# W7U
Low

การทำงาน	คำสั่ง Windows (Bash)
🟢 เริ่ม (Start)	sudo docker-compose -f windows.yml start
🔴 หยุด (Stop)	sudo docker-compose -f windows.yml stop
🔄 รีสตาร์ท (Restart)	sudo docker-compose -f windows.yml restart

การทำงาน คำสั่ง Linux (Bash)
🟢 เริ่ม sudo docker-compose -f linux.yml start
🔴 หยุด sudo docker-compose -f linux.yml stop
🔄 รีสตาร์ท sudo docker-compose -f linux.yml restart

🚀 ขั้นตอนการติดตั้ง

เลือกคำสั่งตามระบบปฏิบัติการที่คุณต้องการติดตั้ง:

🪟 Windows

mkdir user && cd user
wget -O windows.yml https://raw.githubusercontent.com/COCOSzx1245/OStest/refs/heads/main/windows.yml
sudo docker-compose -f windows.yml up


🐧 Linux

mkdir user && cd user
wget -O linux.yml https://raw.githubusercontent.com/COCOSzx1245/OStest/refs/heads/main/linux.yml
sudo docker-compose -f linux.yml up
