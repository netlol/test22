```mermaid
graph TD;
    A-->B;
    A-->C;
    B-->D;
    C-->D;
```


# 流程：
```mermaid
graph TD;
  A[開始] -->|文件維護人員編撰新文件| B(撰寫草稿);
  A -->|文件維護人員編修已存在之文件| C(checkout要編修之文件);
  B -->|與他人共筆| D(與他人共筆);
  B -->|不與他人共筆| E(完成文件);
  C -->|與他人共筆| D(與他人共筆);
  C -->|不與他人共筆| E;
  D --> E;
  E --> F(陳核/定稿);
  F --> G(文件維護人員轉換/檢查markdown格式);
  G --> H(checkin至stage 分支);
  H -->|文件管理人員檢視沒有問題| I(文件管理人員將文件合併至main分支);
  H -->|文件管理人員檢視發現問題| G;
  I --> J(結束);
  ```



- [ ] A
- [ ] B
- [ ] C
- [x] A
- [x] B
- [x] C

| 靠左對齊 | 置中對齊 | 靠右對齊 |
|-----------|:-----------:|--------------------------------:|
| Cell A1 | Cell A2 | Cell A3 |
| Cell B1 | Cell B2 | Cell B3<br/>second line of text |

\


| 1 | 1 | 2 |
| - | - | - |
| 1 | 1 | 2 |
| 2 | 1 | 2 |
| 2 | 1 | 2 |

| Heading 1 | Heading 2 | Heading 3 |
|-----------|-----------|---------------------------------|


# H1

This is a [book](url)
---

    AAAAA
BBBBB

>這段與法就是這要\
>123123123

I工作坊\
123

## H2

* Item\
  IIII
  DDDD
  
- Item

### H3

1. 
  - sub1
  - sub2

2. 23
3. `xx`
4. **xx**

   >testtesttest



4. 34



6. 


<details>
    <summary>點擊我可開啟完整內容</summary>

    <img width="114" alt="image" src="https://user-images.githubusercontent.com/33304953/280638146-526a2ac1-7879-4479-a8fe-de8c045bce49.png" >

</details>




#### H4

**TEXT**\
*TEXT*\
~~TEXT~~

##### H5

```bat
@echo asad

```

###### H6
