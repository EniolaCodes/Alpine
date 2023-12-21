# To-Do-App 

## Table of contents 
  - [Links](#links)
   - [Built with](#built-with)
    - [What I learned](#what-i-learned)
    - [Continued development](#continued-development) -
    - [Useful resources](#useful-resources) -
    -  [Author](#author)
     
### Links
        . [Solution URL](https://github.com/EniolaCodes/To-Do-App)
       . [Live Site URL](https://glowing-travesseiro-55a173.netlify.app)
       
  ### Built with
       . Semantic HTML5 markup
        . CSS
       . JavaScript
       
  ### What I learned
        I enjoyed using the css below to blend the backgroud image with the color, it gave the text a nice appeal.
     
        CSS
          #newTaskSubmit{
        color: var(--pink);
        font-size: 1.25rem;
       font-weight: 700;
       background-image: linear-gradient(to right, var(--pink), var(--purple));
       -webkit-background-clip: text;
        -webkit-text-fill-color: transparent;
       cursor: pointer;
       transition: 0.4s;
       }
       
       JavaScript
       I used the function below to create the edit button. I achieved this with the "readonly" attribute. It was quite a discovery.
       
        taskItemActionsEdit.addEventListener("click", () =>
       { if(taskItemActionsEdit.innerText.toLowerCase() == "edit")
       { taskItemContentInput.removeAttribute("readonly");
       taskItemContentInput.focus();
       taskItemActionsEdit.innerText = "save";
       }
       else{
       taskItemContentInput.setAttribute("readonly", "readonly");
        taskItemActionsEdit.innerText = "Edit"; }
       })
      
  ### Continued development
       DOM Manipulation
      Functions
### Useful resources
. [Example resource 1](https://www.w3schools.com/howto/howto_js_todolist.asp) - This helped in having an idea of how to approach the project. 

## Author
. Website - [Fatimah Adebimpe]

