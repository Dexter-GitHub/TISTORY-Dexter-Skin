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
