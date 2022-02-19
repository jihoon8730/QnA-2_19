# input창 부분 onkeyup을 사용해 아무 입력을 해도 filter()라는 함수를 사용하게 함
# filter()부분 함수
 function filter() {
      let value = $('#input-search').val();
      let item = $('.card');
      let name 
      console.log(value);
      for(i = 0; i < item.length; i++) {
        name = item[i].getElementsByClassName('card-title');
        console.log(name[0].innerHTML);
      }
    }
    
