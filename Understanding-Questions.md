# Understanding Questions:
1. What are the steps of execution from the pressing of the 1 button to the rendering of our updated value? List what part of the code excutes for each step.
* The user presses the 1 button.
* Action within the event handler is executed.
<!-- const handleOneClick = () => {
    dispatch(addOne());
  } -->
* It creats our action package 
<!-- export const addOne = () => {
    return({type:ADD_ONE});
}  -->
* then we move inside of our reducer, depending on the type a specific case will be executed.

<!-- case(ADD_ONE):
            return({
                ...state,
                total: state.total + 1
            }); -->
* lastly returning a new updated state.  
* rerending the application with the new total.
* TotalDisplay shows the total plus 1.
