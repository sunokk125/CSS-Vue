<template>
    <div class="menu_wrapper">
        <div class="menu">
            메뉴1
            <div>
                <p>서브메뉴1</p>
                <p>서브메뉴2</p>
            </div>
        </div>
        <div class="menu">
            메뉴1
            <div>
                <p>서브메뉴1</p>
                <p>서브메뉴2</p>
            </div>
        </div>
        <div class="menu">
            메뉴1
            <div>
                <p>서브메뉴1</p>
                <p>서브메뉴2</p>
            </div>
        </div>
        
    </div>
</template>
<script>
export default {
    
}
</script>
<style>
    .menu_wrapper{
        width:100%;
        display:flex;
        justify-content: center;
    }
    .menu{
        width:10%;
    }
    ul{
        width:100%;
        list-style:none;
    }
    li{
        margin: 0 5%;
        border: 1px solid #cccccc;
        height: 50px;
        text-align: center;
        line-height: 50px;
    }
</style>