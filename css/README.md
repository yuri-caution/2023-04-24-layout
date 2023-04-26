# 웹사이트 레이아웃 만들기

### 웹사이트 레이아웃 8가지

#### 레이아웃 9 콘텐츠 배치
/* contents */
.contents {
    width: 1040px;
    margin: 100px auto;
    display: flex;
    gap: 64px;
}

.contents .photos {
    /* flex: 1; */
    display: flex;
    gap: 20px;
}

.contents .photos .left {
    /* flex: 1; */
    display: flex;
    flex-direction: column;
    gap: 20px;
}

.contents .photos .left .item {
    flex: 1;
}

.contents.photos .right {
    /* flex: 1; */
}

.contents .text_box {
    /* flex: 1; */
}

.contents .text_box h3 {
    font-size: 24px;
    font-weight: bold;
}

.contents .text_box p {
    margin: 32px 70px 40px 0;
}

.contents .text_box a {
    display: block;
    width: 160px;
    height: 40px;
    background-color: #B28C68;
    border: 1px solid #B28C68;
    color: #fff;
    line-height: 40px;
    text-align: center;
}

