<template>
    <mdb-container>
        <select class="browser-default custom-select m-3">
            <option selected disabled>Selectează destinația</option>
            <option value="1">Egipt</option>
            <option value="2">Grecia</option>
            <option value="3">Turcia</option>
        </select>
        <mdb-row class="m-6">
            <mdb-card-group deck>
                <mdb-card>
                    <mdb-view hover>
                        <a href="#!">
                            <mdb-card-image src="https://mdbootstrap.com/img/Photos/Others/images/16.jpg" alt="Card image cap"></mdb-card-image>
                            <mdb-mask flex-center waves overlay="white-slight"></mdb-mask>
                        </a>
                    </mdb-view>
                    <mdb-card-body>
                        <mdb-card-title>Hotel 1</mdb-card-title>
                        <mdb-card-text>Some quick example text to build on the card title and make up the bulk of the
                            card's content.</mdb-card-text>

                        <mdb-btn color="secondary">Alege hotelul</mdb-btn>
                    </mdb-card-body>
                </mdb-card>
                <mdb-card>
                    <mdb-view hover>
                        <a href="#!">
                            <mdb-card-image src="https://mdbootstrap.com/img/Photos/Others/images/14.jpg" alt="Card image cap"></mdb-card-image>
                            <mdb-mask flex-center waves overlay="white-slight"></mdb-mask>
                        </a>
                    </mdb-view>
                    <mdb-card-body>
                        <mdb-card-title>Hotel 2</mdb-card-title>
                        <mdb-card-text>Some quick example text to build on the card title and make up the bulk of the
                            card's content.</mdb-card-text>
                        <mdb-btn color="secondary">Alege hotelul</mdb-btn>
                    </mdb-card-body>
                </mdb-card>
                <mdb-card>
                    <mdb-view hover>
                        <a href="#!">
                            <mdb-card-image src="https://mdbootstrap.com/img/Photos/Others/images/15.jpg" alt="Card image cap"></mdb-card-image>
                            <mdb-mask flex-center waves overlay="white-slight"></mdb-mask>
                        </a>
                    </mdb-view>
                    <mdb-card-body>
                        <mdb-card-title>Hotel 3</mdb-card-title>
                        <mdb-card-text>Some quick example text to build on the card title and make up the bulk of the
                            card's content.</mdb-card-text>
                        <mdb-btn color="secondary">Alege hotelul</mdb-btn>
                    </mdb-card-body>
                </mdb-card>
                <mdb-card>
                    <mdb-view hover>
                        <a href="#!">
                            <mdb-card-image src="https://mdbootstrap.com/img/Photos/Others/images/15.jpg" alt="Card image cap"></mdb-card-image>
                            <mdb-mask flex-center waves overlay="white-slight"></mdb-mask>
                        </a>
                    </mdb-view>
                    <mdb-card-body>
                        <mdb-card-title>Hotel 4</mdb-card-title>
                        <mdb-card-text>Some quick example text to build on the card title and make up the bulk of the
                            card's content.</mdb-card-text>
                        <mdb-btn color="secondary">Alege hotelul</mdb-btn>
                    </mdb-card-body>
                </mdb-card>
            </mdb-card-group>
        </mdb-row>
    </mdb-container>
</template>

<script>
    import { mdbContainer, mdbRow, mdbCard, mdbCardImage, mdbCardBody, mdbCardTitle, mdbCardText, mdbCardGroup, mdbBtn, mdbView, mdbMask} from 'mdbvue';
    export default {
        name: 'CardProPage',
        components: {
            mdbContainer,
            mdbRow,
            mdbCard,
            mdbCardImage,
            mdbCardBody,
            mdbCardTitle,
            mdbCardText,
            mdbCardGroup,
            mdbBtn,
            mdbView,
            mdbMask
        }
    }
</script>