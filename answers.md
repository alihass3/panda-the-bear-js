answer to question1
var image=document.querySelector('img');
image.src=" images/self-portrait-officebg.jpg";

answer to question 1b
var image=document.querySelectorAll('img');
var photo=image[1];
photo.src="http://bitmakerlabs.github.io/panda-the-bear-js/images/pikachu-drawing.jpg";


answer to question 2
var title = document.querySelector('h1')

title.innerText = "Hassan ";

answer to question3
var employment = document.querySelector('#employment > h3');
employment.innerText="COOl";

answer to q4
var document.body.style.backgroundColor = 'blue';

answer to q5.
var highlight = document.querySelectorAll('.highlight');
highlight.forEach(function(text) { text.style.background = 'orange'; });

answer to q6.
var change = document.querySelector('h1');
change.style.fontFamily= 'monospace';

answer to q7
var change = document.querySelector('.action-icon-bg');
change.style.backgroundColor='blue';

answer to q8
var change = document.querySelector('.contact-info');
change.placeholder="Identify yourself";

answer to q9
same as above.

answer to q10
var change = document.querySelector('.contact-info');
change.name="nemesis";


answer to q11
change.setAttribute('value', 'koalathebear@gmail.com');


answer to q12
same as above.

answer to q13.
change.disabled=true;


answer to q14.
var personalinfo = document.querySelector('ul.bio-info');
personalinfo.remove('bio-info-value');
