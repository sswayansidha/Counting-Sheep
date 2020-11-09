## Welcome!
To view the "Counting Sheep" problem,[Click Here.](https://codingcompetitions.withgoogle.com/codejam/round/0000000000201bee/0000000000201c8a)
### Code in Python 3

```markdown
x = input()

num=x

num_str = str(num)

y = {0,1,2,3,4,5,6,7,8,9}

x = set(list(map(int, list(str(x)))))

i=2

if num == 0:

    print("INSOMNIA")

while True:

    if x==y:

        break

    else:

        x = str(num_str) + str(int(num)*i)

        num_str = x

        x = set(list(map(int, list(str(x)))))

        i=i+1

print(str(int(num)*(i-1)))
```

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/sswayansidha/Counting-Sheep/settings). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://docs.github.com/categories/github-pages-basics/) or [contact support](https://github.com/contact) and we’ll help you sort it out.
