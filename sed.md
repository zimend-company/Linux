
```
echo "bash scripting language" | sed 's/bash/perl/g'

sed 's/Sunday/Sunday is Holiday/' weekday.txt

```

## 1 => 

```
py.txt

python is a very popular lang
python is easy. python is easy to learn
python is cross-platform. 

```

// only second line pythons change
> sed '2 s/python/perl/g' py.txt

// the second item change in each line
> sed 's/python/perl/g2'  py.txt

