<template>

<div>
 <h1>Question2</h1>   

<center><table>

<thead>

<tr>

<th></th>

</tr>

</thead>

<tbody>

<tr v-for="data in table_data" :key="data.id">

<td>Name :{{data.name}}</td>

<td>Description : {{data.description}}</td>

<td>Data_Of_Experience : {{data.year_of_experience}}</td>

<td>Location :{{data.location}}</td>

</tr>

</tbody>

</table></center>

</div>

</template>


<script>

export default {

name:"displayData",

data()

{

return{

table_data:[{

"name":"Agile CRM",

"description" : "A company of excellence",

"year_of_experience" : 12,

"location" : "Hyderabad"

}]

}

}

}

</script>

