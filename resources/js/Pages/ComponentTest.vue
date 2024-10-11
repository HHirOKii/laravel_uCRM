<script setup>
    import GuestLayout from '@/Layouts/GuestLayout.vue';
    import Label from '@/Components/InputLabel.vue';
    import InputText from '@/Components/TextInput.vue';

    const emitTest = e => console.log(e);
</script>

<template>
    <GuestLayout>
        <Label value="件名">
            タイトル
        </Label>
        <InputText modelValue=初期値が入ります
        @update:modelValue="emitTest"
        ></InputText>
    </GuestLayout>
</template>