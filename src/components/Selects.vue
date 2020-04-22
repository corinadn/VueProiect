<template>
    <mdb-row>
        <mdb-col md="11" class="pb-2 p-3 m-5">
            <mdb-card class="purple-text grey lighten-4">
                <mdb-card-header class="pt-4 white">
                    <mdb-card-title><strong>Detalii</strong></mdb-card-title>
                </mdb-card-header>
                <mdb-card-body>
                    <mdb-row>
                        <mdb-col>
                            <mdb-input :min="0" :max="20" icon="edit" far type="number" label="nopți" v-model="nopti"/>
                            <mdb-input :min="0" :max="10" icon="edit" far type="number" label="adulti" v-model="adulti"/>
                            <mdb-input :min="0" :max="10" icon="edit" far type="number" label="copii" v-model="copii"/>
                            <mdb-input label="nume" far icon="user" placeholder="John Smith"/>
                            <mdb-textarea :rows="4" label="comentarii" far icon="comment" placeholder="Număr cu vederea spre mare"/>
                        </mdb-col>
                    </mdb-row>
                </mdb-card-body>
                <mdb-card-footer class="d-flex white justify-content-end">
                    <mdb-btn outline="purple" icon="paper-plane">Plasează comanda</mdb-btn>
                </mdb-card-footer>
            </mdb-card>
        </mdb-col>
    </mdb-row>
</template>

<script>
    import { mdbRow, mdbCol, mdbInput, mdbTextarea, mdbBtn, mdbCard, mdbCardHeader, mdbCardTitle, mdbCardFooter, mdbCardBody } from 'mdbvue';

    export default {
        name: 'FormsPage',
        components: {
            mdbRow,
            mdbCol,
            mdbInput,
            mdbTextarea,
            mdbBtn,
            mdbCard,
            mdbCardBody,
            mdbCardHeader,
            mdbCardFooter,
            mdbCardTitle
        },
        data() {
            return {
                guests: 0
            };
        }
    };
</script>