# 关于我们

我们只是一群热爱技术也希望通过技术改变生活的小朋友，希望本站的内容能帮助到你。

如果你愿意联系我们，请运行以下代码后获取我们的联系方式。

```python
import math
from datetime import datetime
from random import choice


def who_we_are():
    print("Hi, how are you？")
    today = datetime.now().today().strftime('%Y%m%d')
    life = choice(range(0, int(today)))  # life is a random number between 0 and today

    life = math.sin(life)  # we all have sin
    life = math.floor(life)  # we all have sadness
    life = math.ceil(life)  # we all have happiness
    life = math.pow(life, life)  # we all have power
    life = math.fabs(life)  # life is absolute positive

    # let's meet in GitHub with code + you
    home = 'https://{}.github.io/'
    team = 'talk-cheap'
    me = int(life) + 1
    you = 'you'
    return home.format(team) + str(me) + you
```