<template>
    <div>
        <h5>Componente Opções</h5>
        <p>Poderiamos recuperar as opções do serviço id</p>
    </div>
</template>

<script>
export default {
    name: 'Opcoes',
    props: ['id'],
    created() {
        console.log('Parâmetro via props', this.id)
    }
}
</script>