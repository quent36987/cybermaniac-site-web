<script>
</script>

<div class="page">
    <iframe
            src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d1177.4808507534615!2d4.41848449624177!3d45.418671087137064!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x47f5a91384d12ab7%3A0x1aa837c59bcf3f77!2s72%20Bd%20Alexandre%20de%20Fraissinette%2C%2042100%20Saint-%C3%89tienne!5e0!3m2!1sen!2sfr!4v1693817451366!5m2!1sen!2sfr"
            width="600"
            height="450"
            style="border:0;"
            allowfullscreen=""
            loading="lazy"
            referrerpolicy="no-referrer-when-downgrade"
    />

    <section class="parking-info">
        <h2>Parking gratuit à proximité</h2>
        <p class="p">Déplacement à domicile possible les lundi, mercredi et vendredi.</p>
    </section>

    <table class="ordi">
        <thead>
        <tr>
            <th/>
            <th>LUNDI</th>
            <th>MARDI</th>
            <th>MERCREDI</th>
            <th>JEUDI</th>
            <th>VENDREDI</th>
            <th>SAMEDI</th>
            <th>DIMANCHE</th>
        </tr>
        </thead>
        <tbody>
        <tr>
            <td>MATIN</td>
            <td>9h00 - 12h00</td>
            <td>9h00 - 12h00</td>
            <td>9h00 - 12h00</td>
            <td>9h00 - 12h00</td>
            <td>9h00 - 12h00</td>
            <td>sur rdv</td>
            <td/>
        </tr>
        <tr>
            <td>APRES-MIDI</td>
            <td>14h00 - 19h00</td>
            <td>14h00 - 19h00</td>
            <td>14h00 - 19h00</td>
            <td>14h00 - 19h00</td>
            <td>14h00 - 19h00</td>
            <td>sur rdv</td>
            <td/>
        </tr>
        </tbody>
    </table>


    <table class="mobile">
        <thead>
        <tr>
            <th></th>
            <th>MATIN</th>
            <th>APRES-MIDI</th>
        </tr>
        </thead>
        <tbody>
        <tr>
            <td>LUNDI</td>
            <td>9h00 - 12h00</td>
            <td>14h00 - 19h00</td>
        </tr>
        <tr>
            <td>MARDI</td>
            <td>9h00 - 12h00</td>
            <td>14h00 - 19h00</td>
        </tr>
        <tr>
            <td>MERCREDI</td>
            <td>9h00 - 12h00</td>
            <td>14h00 - 19h00</td>
        </tr>
        <tr>
            <td>JEUDI</td>
            <td>9h00 - 12h00</td>
            <td>14h00 - 19h00</td>
        </tr>
        <tr>
            <td>VENDREDI</td>
            <td>9h00 - 12h00</td>
            <td>14h00 - 19h00</td>
        </tr>
        <tr>
            <td>SAMEDI</td>
            <td>sur rdv</td>
            <td>sur rdv</td>
        </tr>
        <tr>
            <td>DIMANCHE</td>
            <td></td>
            <td></td>
        </tr>
        </tbody>
    </table>

</div>

<style>
    iframe {
        max-width: 90%;
    }

    .page {
        display: flex;
        flex-direction: column;
        align-items: center;
        justify-content: center;
    }

    .parking-info {
        margin-bottom: 2rem;
    }

    table {
        width: 100%;
        border-collapse: collapse;
        max-width: min(700px, 80vw);
    }

    table,
    th,
    td {
        border: 1px solid #000;
    }

    th,
    td {
        padding: 8px 12px;
        text-align: center;
    }

    th {
        background-color: #f2f2f2;
    }

    .mobile {

        font-size: 0.6rem;
    }

    @media screen and (max-width: 650px) {
        .ordi {
            display: none;
        }

        .parking-info {
            font-size: 0.9rem;
        }

        .p {
            font-size: 0.9rem;
        }
    }

    @media screen and (min-width: 650px) {
        .mobile {
            display: none;

        }
    }

</style>
