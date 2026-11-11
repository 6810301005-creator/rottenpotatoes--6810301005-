# Rotten Potatoes (310-2205 วิศวกรรมซอฟต์แวร์ 2/2569)

Template repository for Lab L1 (310-2205 Software Engineering, semester 2/2569).

![ci](https://github.com/6810301005-creator/rottenpotatoes--6810301005-/actions/workflows/ci.yml/badge.svg)

แก้ `<you>/<repo>` ในบรรทัดบนเป็นชื่อ GitHub และชื่อ repository ของคุณ
(Replace `<you>/<repo>` above with your GitHub user and repository name.)

## เริ่มที่นี่ (Start here)

1. เข้าสู่ระบบ GitHub แล้วกดปุ่ม **Use this template** ด้านขวาบน เลือก **Create a new repository**
2. Owner = บัญชีของคุณ, Repository name = `rottenpotatoes-<รหัสนักศึกษา>`, Public, ไม่ติ๊ก Include all branches แล้วกด **Create repository from template**
3. เปิด IntelliJ IDEA กด **Clone Repository**, เลือก GitHub ด้านซ้าย, เลือก repository ใหม่ของคุณ, กด Clone แล้วกด **Trust Project**
4. เปิด Terminal ใน IntelliJ แล้วรัน `./mvnw -B verify` (Windows: `mvnw.cmd -B verify`) ต้องจบด้วย `BUILD SUCCESS`
5. ทำ Lab L1 ตามสไลด์ แล้วกรอก `docs/L1.md`

(Sign in, use this template to create `rottenpotatoes-<student id>` under your own account, clone it in IntelliJ IDEA, run `./mvnw -B verify`, then follow the L1 slides.)

## วิธี build

How to build. Requires JDK 25 (check with `java -version`).

```bash
./mvnw -B verify      # macOS / Linux
mvnw.cmd -B verify    # Windows