
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

<p dir="rtl" align="right">در sed هر بار دستور برای هر خط جداگانه اجرا می شود</p>

## 2 => 

```
lang.txt

bash programming language. python programming language. perl programming language.
hypertext markup language.
extensible markup language.

```

> sed 's/\(.*\)programming/\1scripting/g' lang.txt

<p dir="rtl" align="right">کد بالا آخربن موردی که اتفاق افتاده در هر خط را جایگزین می کند</p>

> sed -e '$s/python/perl/g' python.txt

> sed '1s/python/perl/g' python.txt



