<template>
    <div>
        <div class="row mb-5">
            <div class="col-3">
                <div class="list-group mb-5">
                    <router-link tag="li" class="nav-link" :to="{name:'orderingGuideLink'}">
                        <a class="list-group-item list-group-item-action">点餐指南</a>
                    </router-link>
                    <router-link tag="li" class="nav-link" :to="{name:'historyLink'}">
                        <a class="list-group-item list-group-item-action">历史订单</a>
                    </router-link>
                    <router-link tag="li" class="nav-link" :to="{name:'deliveryLink'}">
                        <a class="list-group-item list-group-item-action">送餐信息</a>
                    </router-link>
                    <router-link tag="li" class="nav-link" :to="{name:'contactLink'}">
                        <a class="list-group-item list-group-item-action">联系我们</a>
                    </router-link>
                </div>
            </div>
            <div class="col-9">
                <router-view></router-view>
            </div>
        </div>
    </div>
</template>