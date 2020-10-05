vue <template>
    <div class="container">
        <h3>Todos</h3>
    </div>
</template>

<script>
import { mapGetters } from 'vuex';

export default {
    name: "Todos", 
    computed: mapGetters(['allTodos'])
};
</script>

<style scoped> 
    body {
        font-family: "Franklin Gothic Medium", "Arial Narrow", Arial, sans-serif;
        line-height: 1.6;
        background: #e8f7f0;
    }

    .container {
        max-width: 1100px;
        margin: auto;
        overflow: auto;
        padding: 0 2rem;
    }
</style>



