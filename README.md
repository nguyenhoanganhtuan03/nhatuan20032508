 # Hi, I’m Anh Tuan
- 👀 I’m interested in Artificial Intelligence - Computer Vision
- 🌱 I’m currently learning Computer Science - [Can Tho University](https://www.ctu.edu.vn)
- 💞️ I like anime, manga, new technology, games, books, ...

```py
from datetime import datetime

dob = "25/8/2003"
dob = datetime.strptime(dob, "%d/%m/%Y")
today = datetime.now()
age = today.year - dob.year - ((today.month, today.day) < (dob.month, dob.day))

name = "Nguyễn Hoàng Anh Tuấn"
dob = "25/8/2003"
dream = "Computer Science Engineer - Computer Vision"
languages = ["C++", "Python","..."]
libraries = ["OpenCV", "TensorFlow","..."]

print(f"Hello, my name is {name}, I was born on {dob} and I'm {age} years old. My dream is {dream}. "
      f"I can code in {', '.join(languages)} and often use the libraries {', '.join(libraries)}.")

```
  # --> _Learning is the eye of the mind_

<!---
nhatuan20032508/nhatuan20032508 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
