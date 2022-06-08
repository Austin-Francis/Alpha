$(document).ready(function () 
{
    // somehow first navpill will not look active on page load (although it is...)
    $('.navpill.active').trigger('click');
});

<li class="nav-item active"><a class="nav-link active" ....
                               
$(".nav-tabs li a").click(function(){
  $(".nav-tabs li a").removeClass("active");
  $(this).addClass("active");
});
