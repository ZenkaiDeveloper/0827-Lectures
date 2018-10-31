1. 1
2. Good question.
3. State changes inside its component while props are constant values or functions that are passed down from the parent.
4. You can use both when trying to pass information from child to parent, but only need to use props when passing from parent to child.
5. Use constructor when state is dependent on props coming from parents.
6. Pass props as attributes in the parent component.
7. By passing a callback as a prop to a child so that the child can pass an argument into the callback to set the parent's state.
