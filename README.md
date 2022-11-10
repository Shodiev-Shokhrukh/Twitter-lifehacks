# Tweeter-lifehacks


#1 How to delete all your tweeter likes

  1)First, launch Chrome.
  
  2)Then, log into your Twitter account.
  
  3)Navigate to the “Likes” section.
  
  4)Once you’re on the “Likes” page, hit F12. This command will open Chrome’s debug console.
  
  5)Next, click on “Console” to open the tab.
  
  6)Copy this script : ” setInterval(() => { for (const d of document.querySelectorAll('div[data-testid="unlike"]')) { d.click() } window.scrollTo(0, document.body.scrollHeight) }, 1000) ” without quotes into the “Console” field, next to the blue arrow
  
  7)Hit “Enter” and run it.
  
  8)Check the results.
  
  9)Repeat the process as many times as needed.
