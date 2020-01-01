## Usage 

1. `pip install javalang`
2. move `.jar` files to `.m2`
3. `python decomplie_jar.py`
4. `python scanner.py`
5. check results in `result.txt`

##python
decomplie_jar 反编译本地jar

scanner 扫描反编译生成的源文件

## fastjosn 两个 RCE gadgets

###CommonsConfiguration poc
CommonsConfiguration 依赖
>        <dependency>
>             <groupId>commons-configuration</groupId>
>            <artifactId>commons-configuration</artifactId>
>             <version>1.10</version>
>        </dependency>

### Ojdbc14
Ojdbc14 依赖

>       <dependency>
>            <groupId>oracle</groupId>
>           <artifactId>ojdbc14</artifactId>
>           <version>10.2.0.2</version>
>       </dependency>
>        <dependency>
>            <groupId>javax.resource</groupId>
>            <artifactId>javax.resource-api</artifactId>
>            <version>1.7.1</version>
>       </dependency>
