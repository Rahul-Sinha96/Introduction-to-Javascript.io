// Array of names
const names = ["Alice", "Bob", "John", "Jane", "Mike", "Zoe"];

// Loop over the array of names
for (let i = 0; i < names.length; i++) {
    const name = names[i];
    
    // Check if the name starts with 'J' or 'j'
    if (name.charAt(0).toLowerCase() === 'j') {
        console.log(`Goodbye ${name}`);
    } else {
        console.log(`Hello ${name}`);
    }
}
