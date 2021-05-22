---
---

<style>

.container-1{
    display: flex;
    justify-content: space-between;
    width: 1000px;
}


.container-1 div{
    border:1px #ccc solid;
    padding: 10px;
}

.box-1{
    flex:2;
    order:1;
    display: flex;
    flex-direction: column;
    align-items: center;
}

.left-top{

}

.left-mid{
    font-family: Allerta;
    font-style: normal;
    font-weight: normal;
    font-size: 73px;
    line-height: 93px;
    text-align: center;

    color: #075A19;
}

.left-bottom{

}

.box-3{
    order:2;
}

.box-2{
    flex:1;
    order:3;
    display: flex;
    flex-direction: column;
    justify-content: space-around;
    flex-basis: 27%;
}

.right-top{

}

.right-bottom{

}

</style>

<div class="container-1">
    <div class="box-1">
        <div class="left-top">
            <img src="/img/finC.jpg">
        </div>
        <div class="left-mid">
            <img src="/img/iit_roorkee.jpg">
        </div>
        <div class="left-bottom">
            <img src="/img/iitr_vector.png">
        </div>
    </div>
    <div class="box-2">
        <div class="right-top">
            <img src="/img/a_group.png">
        </div>
        <div class="right-bottom">
            <img src="/img/finC_art.png">
        </div>
    </div>
    <div class="box-3">
        <p>
            _____________________
        </p>
    </div>
</div>
