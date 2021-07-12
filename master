import re

filename = "blog_code.txt"

with open(filename, 'r+') as f:
    text = f.read()

### URL rewrites START ---- ###

    text = re.sub('http://radiotimes.com', 'https://wwww.radiotimes.com', text)
    text = re.sub('https://www.radiotimes.com/page1/', 'https://wwww.radiotimes.com/newpage/', text)

### URL rewrites END ---- ###

    f.seek(0)
    f.write(text)
    f.truncate()
