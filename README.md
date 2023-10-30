# TISTORY-Dexter-Skin
> Tistory Skin Customizing
</br>

## 파일구조
</br>

```
SKIN ─┬─ index.xml   
      ├─ skin.html   
      ├─ style.css   
      ├─ preview.gif   
      ├─ preview256.jpg   
      ├─ preview560.jpg   
      ├─ preview1600.jpg   
      └─ images ─┬─ script.js   
                 ├─ background.jpg   
                 ├─ background.jpg   
                 └─ background.jpg
```  
</br>

## 파일구조 상세내용

### index.xml
스킨에 필요한 정보를 담고 있는 xml 파일로 이 파일이 변경되면 스킨의 모든 설정이 초기화됩니다.
</br>

### skin.html
스킨의 메인 템플릿 파일로 치환자를 사용해 각 url에 해당하는 HTML 결과물로 치환됩니다.
</br>

### style.css
css 분리를 위한 파일이며 skin.html과 마찬가지로 스킨에디터에서 편집할 수 있습니다.
</br>

### preview
티스토리 각 영역에서 미리보기를 표시하기 위한 파일입니다.
</br>

* preview.gif : 미리보기 기본 파일로 아래 파일이 없는 경우에 사용 (112x84)
* preview256.jpg : 사용 중인 스킨 미리보기 (256x192)
* preview560.jpg : 스킨 목록 미리보기 (560x420)
* preview1600.jpg : 스킨 상세보기 미리보기 (1600x1200)

  
### images
필수요소가 아닌 파일은 모두 images 아래에 위치하게 됩니다. image, script, css 등을 업로드하여 스킨에서 사용합니다.
<br>

## 공통 치환자

### 스킨 치환자 그룹

* <s_t3>: 티스토리 공통 javascript 삽입(필수)
<br>

### 기본 정보
#### 블로그 정보

* [##_title_##] : 블로그 제목
* [##_image_##] : 블로그 대표 이미지 url
* [##_blog_image_##] : 블로그 대표 이미지를 포함한 IMG 태그
* [##_desc_##] : 블로그 설명
* [##_blogger_##] : 블로그 소유자의 필명

#### 블로그 URL

* [##_blog_link_##] : 블로그 url
* [##_res_url_##] : rss feed 주소
* [##_taglog_link_##] : 태그로그 url
* [##_guestbook_link_##] : 방명록 url

#### 기타

* [##_page_title_##] : 페이지 제목
* [##_blog_menu_##] : 블로그 메뉴 리스트
* [##_body_id_##] : 페이지 타입에 따른 id
  
|페이지 타입|body_id|
|------------|-------|
|홈화면|tt-body-index|
|글화면|tt-body-page|
|카테고리 글 리스트|tt-body-category|
|보관함 글 리스트|tt-body-archive|
|태그 리스트|tt-body-tag|
|검색결과 리스트|tt-body-search|
|방명록|tt-body-guestbook|
|지역로그|tt-body-location|
<br>

### 광고 치환자
* [##revenue_list_upper##] : 블로그 홈/목록 상단
* [##revenue_list_lower##] : 블로그 홈/목록 하단



