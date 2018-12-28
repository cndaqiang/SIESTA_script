# SIESTA_script
SIESTA_script

## 下载psf

```
getpsf 
```

## POSCAR 转siesta
目前仅支持VESTA生成的POSCAR,不支持固定原子以及包含注释的情况
```
v2s
```

## SIESTA计算结果转CONTCAR

目前仅支持先用`v2s`生成siesta的输入文件, 不支持固定原子以及包含注释的情况
```
s2v
```

