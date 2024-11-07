# anan.js
function toggleStoryWidget(element) {   const stories = document.querySelectorAll('.story-widget');   stories.forEach(story => {     if (story !== element) {       story.classList.remove('open');     }   });   element.classList.toggle('open'); }
