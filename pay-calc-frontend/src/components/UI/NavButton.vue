<template>
    <button>
        <img src="../../assets/account-icon.svg" height="15"/>
        <p>{{ buttonTitle }}</p>
    </button>
</template>

<script>
export default {
    name: 'NavButton',
    props: {
        buttonTitle: String
    }
}
</script>

<style scoped>

button {
    display: flex;
    flex-direction: row;
    align-items: center;
    background-color: #1f1f1f;
    border-radius: 5px;
    border-style: none;
    color: white;
    padding: 5px;
}

p {
    margin: 5px;
}

img {
    margin: 5px;
    filter: invert(81%) sepia(95%) saturate(0%) hue-rotate(121deg) brightness(105%) contrast(105%);
}

</style>