var imgs=new Array();
imgs[0]="pictures/slide1.jpg";
imgs[1]="pictures/slide2.jpg";
imgs[2]="pictures/slide3.jpg";
imgs[3]="pictures/slide4.jpg";
imgs[4]="pictures/slide5.jpg";
var currentPage=1;
var maxPage=5;
var obj=null;
function pre(){
currentPage--;//0 4 3 2 1
if(currentPage<=0){
	currentPage=5;
}
for(var i=1;i<(maxPage+1);i++){
	if(currentPage==i){
		obj.src=imgs[currentPage-1];
	}
 }
}
function next(){
currentPage++;//2 3 4 5 6
if(currentPage>5){
	currentPage=1;
}
for(var i=1;i<(maxPage+1);i++){
	if(currentPage==i){
       obj.src=imgs[currentPage-1];
	}
}
}

window.onload=function(){
	obj=document.getElementById("Img");
};