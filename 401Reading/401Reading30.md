# Class 30 - Reading

## Hash Table Cheat Sheet

### Creating a hashtable

*object literal syntax*
const hashtable = {
  key1: 'val1',
  key2: 'val2',
  key3: 'val3'
};

*object constructor syntax*
const hashtable = new Object();
hashtable.key1 = 'val1';
hashtable.key2 = 'val2';
hashtable.key3 = 'val3';


### Accessing values in hashtable

console.log(hashtable.key1); // output: 'val1'
console.log(hashtable.key2); // output: 'val2'
console.log(hashtable.key3); // output: 'val3'


### Adding or updating value in a hashtable

hashtable.key4 = 'val4'; // adds a new key-value pair
hashtable.key3 = 'new val'; // updates the value of an existing key


### Deleting a value from a hashtable

delete hashtable.key3;


### Checking if a key exists in a hashtable

if('key1' in hashtable) {
  console.log('key1 exists');
}


### Iterating over keys and values in a hashtable

for (const key in hashtable) {
  if (hashtable.hasOwnProperty(key)) {
    const val = hashtable[key];
    console.log(`${key}: ${val}`);
  }
}


### Getting the number of key-value pairs in hashtable

const numKeys = Object.keys(hashtable).length;
