
## install
> npm i jquery <br><br>
> npm i px-jquery-pagination


## html
> \<div class="mypages"\>\</div\> <br>

## css
> @import "~px-jquery-pagination/px-pagination.css";

## javascript - jquery
> require('px-jquery-pagination');


### init
> $(".mypages").pagination({ <br>
>            currentpage: 1,<br>
>            totalPageCount: 10,<br>
>            maxBtnCount: 5,<br>
>            align: 'left', /* (left OR center OR right) */<br> 
>            nextPrevBtnShow: true, /* (true OR false) */<br>
>            firstLastBtnShow: true, /* (true OR false) */<br>
>            prevPageName: '<',<br>
>            nextPageName: '>',<br>
>            lastPageName: '<<',<br>
>            firstPageName: '>>',<br>
>            callback: function(pagenumber){ console.log(pagenumber); }<br>
>        });<br>
<br>

### view:
#### 1.
![alt text](https://raw.githubusercontent.com/PiriAykut/px-filter-box/master/screenshots/Screenshot_1.png)

<br>

#### 2.
![alt text](https://raw.githubusercontent.com/PiriAykut/px-filter-box/master/screenshots/Screenshot_2.png)

<br>
