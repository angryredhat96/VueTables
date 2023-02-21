<template>
    <div className="table-element">
        <div class="scroll-table">
	<table>
		<thead>
			<tr>
				<th className="th-head-col"> </th>
				<th>1</th>
				<th>2</th>
				<th>3</th>
				<th>4</th>
			</tr>
		</thead>
	</table>	
	<div class="scroll-table-body">
		<table>
            <tbody>
			<!-- <tbody v-for="el in rowNum"> -->
				<tr>
					<td className="head-col">1</td>
					<!-- <td className="head-col">{{ el }}</td> -->
					<td><Icon /></td>
					<td><Input /></td>
					<td>3</td>
					<td>4</td>
				</tr>
				<tr>
					<td className="head-col">2</td>
					<td>1</td>
					<td>2</td>
					<td>3</td>
					<td>4</td>
				</tr>
				<tr>
					<td className="head-col">3</td>
					<td>1</td>
					<td>2</td>
					<td>3</td>
					<td>4</td>
				</tr>
				<tr>
					<td className="head-col">4</td>
					<td>1</td>
					<td>2</td>
					<td>3</td>
					<td>4</td>
				</tr>
                <tr>
					<td className="head-col">5</td>
					<td>1</td>
					<td>2</td>
					<td>3</td>
					<td>4</td>
				</tr>
                <tr>
					<td className="head-col">6</td>
					<td>1</td>
					<td>2</td>
					<td>3</td>
					<td>4</td>
				</tr>
                <tr>
					<td className="head-col">7</td>
					<td>1</td>
					<td>2</td>
					<td>3</td>
					<td>4</td>
				</tr>
                <tr>
					<td className="head-col">6</td>
					<td>1</td>
					<td>2</td>
					<td>3</td>
					<td>4</td>
				</tr>
                <tr>
					<td className="head-col">9</td>
					<td><Icon /></td>
					<td><Input /></td>
					<td>3</td>
					<td>4</td>
				</tr>
				<tr>
					<td className="head-col">10</td>
					<td>1</td>
					<td>2</td>
					<td>3</td>
					<td>4</td>
				</tr>
				<tr>
					<td className="head-col">11</td>
					<td>1</td>
					<td>2</td>
					<td>3</td>
					<td>4</td>
				</tr>
				<tr>
					<td className="head-col">12</td>
					<td>1</td>
					<td>2</td>
					<td>3</td>
					<td>4</td>
				</tr>
                <tr>
					<td className="head-col">13</td>
					<td>1</td>
					<td>2</td>
					<td>3</td>
					<td>4</td>
				</tr>
                <tr>
					<td className="head-col">14</td>
					<td>1</td>
					<td>2</td>
					<td>3</td>
					<td>4</td>
				</tr>
                <tr>
					<td className="head-col">15</td>
					<td>1</td>
					<td>2</td>
					<td>3</td>
					<td>4</td>
				</tr>
                <tr>
					<td className="head-col">16</td>
					<td>1</td>
					<td>2</td>
					<td>3</td>
					<td>4</td>
				</tr>
                <tr>
					<td className="head-col">17</td>
					<td><Icon /></td>
					<td><Input /></td>
					<td>3</td>
					<td>4</td>
				</tr>
				<tr>
					<td className="head-col">18</td>
					<td>1</td>
					<td>2</td>
					<td>3</td>
					<td>4</td>
				</tr>
				<tr>
					<td className="head-col">19</td>
					<td>1</td>
					<td>2</td>
					<td>3</td>
					<td>4</td>
				</tr>
				<tr>
					<td className="head-col">20</td>
					<td>1</td>
					<td>2</td>
					<td>3</td>
					<td>4</td>
				</tr>
                <tr>
					<td className="head-col">21</td>
					<td>1</td>
					<td>2</td>
					<td>3</td>
					<td>4</td>
				</tr>
                <tr>
					<td className="head-col">22</td>
					<td>1</td>
					<td>2</td>
					<td>3</td>
					<td>4</td>
				</tr>
                <tr>
					<td className="head-col">23</td>
					<td>1</td>
					<td>2</td>
					<td>3</td>
					<td>4</td>
				</tr>
                <tr>
					<td className="head-col">24</td>
					<td>1</td>
					<td>2</td>
					<td>3</td>
					<td>4</td>
				</tr>
			</tbody>
		</table>
	</div>	
</div>
 </div>
 </template>
 
 <script>
import Icon from '../ui/Icon'
import Input from '../ui/Input'

export default {
    rows () {
       return {
           rowNum : ['1', '2', '3', '4', '5', '6', '7', '8', '9', '10', '11', '12', '13', '14', '15', '16', '17', '18', '19', '20']

       }
    },

 components: {
     Icon, Input
 }
}

 

 </script>
 
 <style>
    
    .scroll-table {
    width: 1000px;
    height: 500px;
}

.scroll-table table {
    width: 100%;
    table-layout: fixed;
    border: none;
    white-space: nowrap;
}


.scroll-table thead th {
    font-weight: bold;
    text-align: left;
    border: none;
    padding: 5px 5px;
    background: #74bec2;
    font-size: 14px;
}

.scroll-table-body {
    overflow-x: scroll;
    height: 440px;
    margin-top: 0px;
    margin-bottom: 20px;
    border-bottom: 1px solid #eee;
}

.scroll-table-body table {
    overflow-y: scroll;
}

.scroll-table-body tbody td {
    text-align: left;
    border-left: 1px solid #ddd;
    border-right: 1px solid #ddd;
    padding: 3px 3px;
    font-size: 14px;
    vertical-align: top;
}

.scroll-table tbody tr:nth-child(even){
    background: #f3f3f3;
}

::-webkit-scrollbar {
    width: 6px;
} 

::-webkit-scrollbar-track {
    box-shadow: inset 0 0 6px rgba(0,0,0,0.3); 
} 

::-webkit-scrollbar-thumb {
    box-shadow: inset 0 0 6px rgba(0,0,0,0.3); 
}

.th-head-col {
    position: sticky;
    width: 40px;
    left: 0;
    top: auto;
    border-top-width: 1px;
    margin-top: -1px;
    gap: 1em;
    transition: 0.3s ease;
    background-color: #74bec2;
    font-weight: bold;
}

.head-col {
    position: sticky;
    width: 40px;
    left: 0;
    top: auto;
    border-top-width: 1px;
    margin-top: -1px;
    gap: 1em;
    transition: 0.3s ease;
    background-color: #74bec2;
    font-weight: bold;
}
 </style>