#### - ??기능 명??  
  
##### 설명

??설명란??  

- method : **??method??**  
- URL : **??end point??**  

##### Request

###### Header

| name | description | required |
|---|:---:|:---:|
| ??필드명?? | ??필드 설명?? | ??필수 여부?? |

###### Request Body

| name | type | description | required |
|---|:---:|:---:|:---:|
| ??필드명?? | ??필드 타입?? | ??필드 설명?? | ??필수 여부?? |

###### Example

```bash
curl -v -X ㅡ??Method?? "??pull url??" \
 -d "??필드명??=값??"
```

##### Response

###### Header

| name | description | required |
|---|:---:|:---:|
| ??필드명?? | ??필드 설명?? | ??필수 여부?? |

###### Response Body

| name | type | description | required |
|---|:---:|:---:|:---:|
| ??필드명?? | ??필드 타입?? | ??필드 설명?? | ??필수 여부?? |

###### Example

**응답 성공**
```bash
HTTP/1.1 ??상태코드?? ??상태메세지??
??필드명??: ??필드값??
{
  "??필드명??": "??필드 값??"
}
```

**응답 : 실패 (??...??)**
```bash
HTTP/1.1 ??상태코드?? ??상태메세지??
??필드명??: ??필드값??
{
  "??필드명??": "??필드 값??"
}
```