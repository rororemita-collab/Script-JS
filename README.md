# Script-JS
var btn_diva = document.getElementById("btn_diva"); 
var btn_divb = document.getElementById("btn_divb"); 
var btn_divc = document.getElementById("btn_divc"); 
 
var diva = document.getElementById("diva"); 
var divb = document.getElementById("divb"); 
var divc = document.getElementById("divc"); 
 
btn_diva.addEventListener('click', ()=>{ 
    diva.style.display = 'block'; 
    divb.style.display = 'none'; 
    divc.style.display = 'none'; 
}) 
 
btn_divb.addEventListener('click', ()=>{ 
    diva.style.display = 'none'; 
    divb.style.display = 'block'; 
    divc.style.display = 'none'; 
}) 
 
btn_divc.addEventListener('click', ()=>{ 
    diva.style.display = 'none'; 
    divb.style.display = 'none'; 
    divc.style.display = 'block'; 
})
