<template>
  <div>
     <g-row>
        <g-col span="8">8</g-col>
        <g-col span="8">8</g-col>
        <g-col span="8">8</g-col>
      </g-row>
      <g-row>
        <g-col span="6">6</g-col>
        <g-col span="6">6</g-col>
        <g-col span="6">6</g-col>
        <g-col span="6">6</g-col>
      </g-row>
      <g-row>
        <g-col span="4">4</g-col>
        <g-col span="4">4</g-col>
        <g-col span="4">4</g-col>
        <g-col span="4">4</g-col>
        <g-col span="4">4</g-col>
        <g-col span="4">4</g-col>
      </g-row>
      <g-row>
        <g-col span="2">2</g-col>
        <g-col span="2">2</g-col>
        <g-col span="2">2</g-col>
        <g-col span="2">2</g-col>
        <g-col span="2">2</g-col>
        <g-col span="2">2</g-col>
        <g-col span="2">2</g-col>
        <g-col span="2">2</g-col>
        <g-col span="2">2</g-col>
        <g-col span="2">2</g-col>
        <g-col span="2">2</g-col>
        <g-col span="2">2</g-col>
      </g-row>
  </div>
</template>

<script>
import Row from '../../../src/row'
import Col from '../../../src/col'
export default {
  components:{
    'g-row': Row,
    'g-col': Col,

  },
  
}
</script>