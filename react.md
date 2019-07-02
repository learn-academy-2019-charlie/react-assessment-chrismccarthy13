# React Assessments

Try your best to answer each question on your own before looking up the answer online. Once you're done writing your first answer, you can google the question and write the best answer you find.

#### 1. Here is a list of pros and cons to using the React library to build your application -- but some of them are false. Remove the false statements from the list:

- React is a modern, efficient answer to complex UI applications
- React is a flexible library that plays the role of V in an MVC framework

 
 #### 2. What are "smart"(logic) and "dumb"(display) components? Explain the difference and also add why we bother to make the distinction between them.
 
 
 //Your Answer
 A smart logic component is when the component has a state. 
 A dumb display component is when the component does not have a state.
 We make the distinction because a state contains key values.
 
 //Googled Answer
 Smart components are app level components that perform functions and manage data while dumb components focus solely on the UI.
 
#### 3. When we use "yarn add ..." in the terminal - what is yarn doing? And what file will always be automatically updated after we add a package with yarn?
 
 
 //Your Answer
 It is used to install a react package. 
 After install a package with yarn, we then create a react app with the name you choose.
 
 //Googled Answer
 In general, a package is simply a folder with code and a package.json file that describes the contents. When you want to use another package, you first need to add it to your dependencies. This means running yarn add [package-name] to install it into your project.
 
#### 5. There are three mistakes in this code that would cause it to break our application. Find the mistakes and fix them:

    class Recipes extends Component {
      constructor(props){
        super(props)
        this.state = {
          recipes:[{name: 'Meatballs'},{name: 'Mac & Cheese'}]
        }
      }
    
      render() {
        let recipes = this.state.recipes.map(function(recipe){
            return(
              <li key={recipe.name}>{recipe.name}</li>
            )
          })
          
        return (
          <ul>
            {recipes}
          </ul>
        );
      }
    }
    
    export default Recipes;

#### 6. Name three html input types. (NOTE: text is the default type - so it doesn't count in this case)
 
 //Your Answer
 Three html input types are password, color, and image.
 
 //Googled Answer
 Three other html input types are date, checkbox, and submit.
 
 #### 7. How would you explain state to a friend who doesn't know code?
 
 //Your Answer
 I would explain state to a friend that doesnt know code as an object with certain attributes or values that you are able to change.
 
 //Googled Answer
 State holds information about the component. However, the kind of information and how it is handled is different.
 When a component needs to keep track of information between renderings the component itself can create, update, and use state.
 
 #### 8. What is the difference between component state and props? Your answer should include a short explanation of both.
 
 
 //Your Answer
 Props are passed in and cannot be changed. State is declared within the component and can be changed.
 
 //Googled Answer
 Props get passed to the component (similar to function parameters) whereas state is managed within the component (similar to variables declared within a function).
   
#### 9. Write a paragraph or so about your experience with building tic-tac-toe. Some topics to start with might be: things you learned about yourself, concepts from React that stood out to you, something about pair programming (if you paired), or the experience of building something in code from scratch.

Everyone in the group did not feel very confident with react at the beginning of the project.
We started building a tic tac toe game following the tutorial on the react website.
This helped us gain a better understanding for when we built our treasure hunt game.
I felt comfortable with react at the beginning, but as we started to add more things, putting it all together became a challenge.
By the end of the project, I felt better about react and understood how different components worked together. 