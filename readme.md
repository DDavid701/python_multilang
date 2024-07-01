# MultiLang (v1.1)

ML is a library for making multi language applications!

```example script.py```
```python
import multilang

language = multilang.get_language()

multilang.set_folder('langs/')

multilang.set_fallback_language('en_EN')

message = multilang.text(language=language, id=1)
print(message)
```

```example en_EN```

```text
1;Welcome!
2;How are you doing?
3;Where do you live?
```

```<ID>;<MESSAGE>```