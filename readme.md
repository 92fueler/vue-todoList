# Todo List 
## mini front-end project by using Vue.js 

#### 1. add a todo item 
##### to generate a list structure --> v-for="(item, index) in list"
##### to get the data from the user's input --> v-model="inputValue" 
##### to add one more todo item by hitting the ENTER key --> v-on:keyup.enter="add"

#### 2. delete a todo item 
##### to delete a item --> click on x icon --> v-on:click="remove("index")

#### 3. calculate the total of items 
##### to get the total number --> this.list.length 

#### 4. clear all the items at once
##### to reset the list empty --> this.list = []

#### 5. hide the footer 
##### to auto hide the footer when there is no item in the list --> v-show="list.length!=0"