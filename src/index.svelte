<script>
  let name1 = "";
  let name2 = "";
  let name3 = "";
  let name4 = "";
  let name5 = "";
  let name6 = "";
</script>

<style>
  .grid-container {
    justify-content: space-between;
    display: grid;
    grid-template-rows: 80px 80px 80px 80px 80px 80px 80px 80px;
    grid-template-columns: 240px 115px 115px 115px 115px 115px 115px 115px 115px 115px 115px;
    padding: 5px;
    text-align: center;
  }

  .grid-item1 {
    background-color: rgba(200, 0, 255, 0.8);
    border: 1px solid rgba(0, 0, 0, 0.8);
    padding: 5px;
    font-size: 20px;
  }
  .grid-item2 {
    background-color: rgba(255, 140, 0, 0.8);
    border: 1px solid rgba(0, 0, 0, 0.8);
    padding: 5px;
    font-size: 20px;
  }
  .grid-item3 {
    background-color: rgb(0, 217, 255);
    border: 1px solid rgba(0, 0, 0, 0.8);
    padding: 5px;
    font-size: 20px;
  }
  .grid-item4 {
    background-color: rgba(234, 255, 0, 0.8);
    border: 1px solid rgba(0, 0, 0, 0.8);
    padding: 5px;
    font-size: 20px;
  }
  .grid-item5 {
    background-color: rgba(255, 0, 38, 0.8);
    border: 1px solid rgba(0, 0, 0, 0.8);
    padding: 5px;
    font-size: 20px;
  }
  .grid-item6 {
    background-color: rgba(34, 0, 255, 0.8);
    border: 1px solid rgba(0, 0, 0, 0.8);
    padding: 5px;
    font-size: 20px;
  }
  .grid-item-jobs {
    grid-column-gap: 10px;
    border: 1px solid rgba(0, 0, 0, 0.8);
    padding: 5px;
    font-size: 20px;
  }
  .grid-item-week {
    grid-column-gap: 10px;
    border: 1px solid rgba(0, 0, 0, 0.8);
    padding: 20px;
    font-size: 20px;
  }
  .flat {
    grid-column-gap: 10px;
    background-color: rgb(96, 250, 165);
    border: 1px solid rgba(0, 0, 0, 0.8);
    padding: 20px;
    font-size: 20px;
  }
  label{
    font-size: 20px;
  }
  .input{
    width: 1000px;
  }
</style>

<br>
<label>
  Student 1:
  <input class="input" bind:value={name1} />
</label>
<br>
<br>
<label>
  Student 2:
  <input class="input" bind:value={name2} />
</label>
<br>
<br>
<label>
  Student 3:
  <input class="input" bind:value={name3} />
</label>
<br>
<br>
<label>
  Student 4:
  <input class="input" bind:value={name4} />
</label>
<br>
<br>
<label>
  Student 5:
  <input class="input" bind:value={name5} />
</label>
<br>
<br>
<label>
  Student 6:
  <input class="input" bind:value={name6} />
</label>

<br />
<br />
<br />

<div class="grid-container">
  <div class="flat">GREEN FLAT</div>
  <div class="grid-item-week">WEEK 1</div>
  <div class="grid-item-week">WEEK 2</div>
  <div class="grid-item-week">WEEK 3</div>
  <div class="grid-item-week">WEEK 4</div>
  <div class="grid-item-week">WEEK 5</div>
  <div class="grid-item-week">WEEK 6</div>
  <div class="grid-item-week">WEEK 7</div>
  <div class="grid-item-week">WEEK 8</div>
  <div class="grid-item-week">WEEK 9</div>
  <div class="grid-item-week">WEEK 10</div>
  <div class="grid-item-jobs">All surfaces to be wipped down and tidied</div>
  <div class="grid-item1">{name1}</div>
  <div class="grid-item2">{name2}</div>
  <div class="grid-item3">{name3}</div>
  <div class="grid-item4">{name4}</div>
  <div class="grid-item5">{name5}</div>
  <div class="grid-item6">{name6}</div>
  <div class="grid-item1">{name1}</div>
  <div class="grid-item2">{name2}</div>
  <div class="grid-item3">{name3}</div>
  <div class="grid-item4">{name4}</div>
  <div class="grid-item-jobs">Take out rubbish</div>
  <div class="grid-item6">{name6}</div>
  <div class="grid-item1">{name1}</div>
  <div class="grid-item2">{name2}</div>
  <div class="grid-item3">{name3}</div>
  <div class="grid-item4">{name4}</div>
  <div class="grid-item5">{name5}</div>
  <div class="grid-item6">{name6}</div>
  <div class="grid-item1">{name1}</div>
  <div class="grid-item2">{name2}</div>
  <div class="grid-item3">{name3}</div>
  <div class="grid-item-jobs">Bathroom towels to the recycling bin</div>
  <div class="grid-item5">{name5}</div>
  <div class="grid-item6">{name6}</div>
  <div class="grid-item1">{name1}</div>
  <div class="grid-item2">{name2}</div>
  <div class="grid-item3">{name3}</div>
  <div class="grid-item4">{name4}</div>
  <div class="grid-item5">{name5}</div>
  <div class="grid-item6">{name6}</div>
  <div class="grid-item1">{name1}</div>
  <div class="grid-item2">{name2}</div>
  <div class="grid-item-jobs">Tidy Kitchen area and compost out</div>
  <div class="grid-item4">{name4}</div>
  <div class="grid-item5">{name5}</div>
  <div class="grid-item6">{name6}</div>
  <div class="grid-item1">{name1}</div>
  <div class="grid-item2">{name2}</div>
  <div class="grid-item3">{name3}</div>
  <div class="grid-item4">{name4}</div>
  <div class="grid-item5">{name5}</div>
  <div class="grid-item6">{name6}</div>
  <div class="grid-item1">{name1}</div>
  <div class="grid-item-jobs">Vacum hallway and lounge</div>
  <div class="grid-item3">{name3}</div>
  <div class="grid-item4">{name4}</div>
  <div class="grid-item5">{name5}</div>
  <div class="grid-item6">{name6}</div>
  <div class="grid-item1">{name1}</div>
  <div class="grid-item2">{name2}</div>
  <div class="grid-item3">{name3}</div>
  <div class="grid-item4">{name4}</div>
  <div class="grid-item5">{name5}</div>
  <div class="grid-item6">{name6}</div>
  <div class="grid-item-jobs">Tidy lounge and out furniture in place</div>
  <div class="grid-item2">{name2}</div>
  <div class="grid-item3">{name3}</div>
  <div class="grid-item4">{name4}</div>
  <div class="grid-item5">{name5}</div>
  <div class="grid-item6">{name6}</div>
  <div class="grid-item1">{name1}</div>
  <div class="grid-item2">{name2}</div>
  <div class="grid-item3">{name3}</div>
  <div class="grid-item4">{name4}</div>
  <div class="grid-item5">{name5}</div>
  <div class="grid-item-jobs">Wash tea towels and tidy laundry</div>
  <div class="grid-item1">{name1}</div>
  <div class="grid-item2">{name2}</div>
  <div class="grid-item3">{name3}</div>
  <div class="grid-item4">{name4}</div>
  <div class="grid-item5">{name5}</div>
  <div class="grid-item6">{name6}</div>
  <div class="grid-item1">{name1}</div>
  <div class="grid-item2">{name2}</div>
  <div class="grid-item3">{name3}</div>
  <div class="grid-item4">{name4}</div>

</div>
