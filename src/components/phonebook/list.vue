<template>
    <div class="phone-list">
        <ul class="flex-column">
            <li class="flex-column">
                    <h2>김다운</h2>
                    <h3>01012341234</h3>
                    <p>서울시 강동구 명일동 1588-123</p>
                <div class="btn_area flex">
                    <span>삭제</span>
                    <span>수정</span>
                </div>
            </li>
        </ul>
    </div>
</template>

<script lang="ts">
import { defineComponent } from 'vue';

interface phoneBook {
    idx:number;
    name:string;
    phone:string;
    address:string;
}

export default defineComponent({
    data(){
        return{
            phoneList:[
                {
                    idx:0,
                    name:'dawoon',
                    phone:'01012341234',
                    address:'서울시 강동구 명일동 1588-123'
                }
            ] as phoneBook[]
        }
    }
})
</script>



<style lang="scss" scoped>
div.phone-list{
    .flex{
        display: flex;
    }
    .flex-column{
        display: flex;
        flex-direction: column;
    }
    ul{
        max-width: 767px;
        width: 100%;
        padding: 0;
        justify-content: center;
        align-items: center;
        li{
            border: 1px solid #222;
            list-style-type: none;
            text-align: left;
            padding: 15px 25px;
            gap: 20px;
            .btn_area{
                gap: 10px;
                justify-content: flex-end;

            }
        }
    }

}
</style>