/**
 *  $(document).ready(function() {
	var i=1; // 변수설정은 함수의 바깥에 설정!
  $("#prdSelect2").click(function() {
    
    $("#thirdSection2").append("<p class='original'>등장"+i+"</p>");
    
    i++; // 함수 내 하단에 증가문 설정
    

  });
});
 */

$(document).ready(function() {
	var i=1;
  $('#prdSelect2').change(function() {
    var result = $('#prdSelect2 option:selected').val();
    if (result == '회색') {
      $('#thirdSection2').append("<div class='original'>등장"+i+"</div>");
    }
  }); 
}); 