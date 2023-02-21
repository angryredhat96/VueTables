<template>
    <div className="table-element">
        <Table v-bind:data="time" />
    </div>
    </template>
    
    <script>
import Table from '../ui/Table'
import Input from '../ui/Input'

export default {
    datalist2 () {
        return {
            time : ['06', '07', '08', '09', '10', '11', '12', '13', '14', '15', '16', '17', '18', '19', '20', '21', '22', '23', '00', '01', '02', '03', '04', '05']
        }
    },
    
        components: {
            Table, Input
        }
    }
    
    </script>
    
    <style>
    .table-element {
    display: flex;
    align-items: center;
    justify-content: center;
    padding: 7px;
    }
    </style>