<!DOCTYPE html>
<html>


    <head>
        <meta charset="utf-8" />
        <meta name="viewport" content="width=device-width, initial-scale=1.0" />
        <title>AllertaLiguria - Homepage</title>
        
        <!-- Importazione CSS -->
        

<link rel="stylesheet" type="text/css" href="css/foundation.min.css" />
<link rel="stylesheet" type="text/css" href="css/jquery-ui.min.css" />

        <link rel="stylesheet" type="text/css" href="css/jquery.smarticker.min.css" />
        <link rel="stylesheet" type="text/css" href="css/styles.css" />
        
        <!-- Importazione librerie Javascript -->
        

<script type="text/javascript" src="js/vendor/jquery.min.js"></script>
<script type="text/javascript" src="js/vendor/jquery-ui.min.js"></script>
<script type="text/javascript" src="js/foundation.min.js"></script>
<script type="text/javascript" src="js/vendor/modernizr.js"></script>

        <script type="text/javascript" src="js/custom/al.accordion.js"></script>
        <script type="text/javascript" src="js/vendor/jquery.smarticker.min.js"></script>
        
        <script type="text/javascript">
        var infoComuni;

        $(function() {
            infoComuni = new Array();

            infoComuni["AIROLE"] = {classificazione: "INTERNO", zona: "A", flag_bacini_piccoli: "Y", flag_bacini_medi: "Y", flag_bacini_grandi: "Y", lista_bacini_piccoli: "", lista_bacini_medi: "", lista_bacini_grandi: "ROJA"};
infoComuni["APRICALE"] = {classificazione: "INTERNO", zona: "A", flag_bacini_piccoli: "Y", flag_bacini_medi: "Y", flag_bacini_grandi: "N", lista_bacini_piccoli: "", lista_bacini_medi: "", lista_bacini_grandi: ""};
infoComuni["AQUILA DI ARROSCIA"] = {classificazione: "INTERNO", zona: "A", flag_bacini_piccoli: "Y", flag_bacini_medi: "Y", flag_bacini_grandi: "N", lista_bacini_piccoli: "", lista_bacini_medi: "", lista_bacini_grandi: ""};
infoComuni["ARMO"] = {classificazione: "INTERNO", zona: "A", flag_bacini_piccoli: "Y", flag_bacini_medi: "N", flag_bacini_grandi: "N", lista_bacini_piccoli: "", lista_bacini_medi: "", lista_bacini_grandi: ""};
infoComuni["AURIGO"] = {classificazione: "INTERNO", zona: "A", flag_bacini_piccoli: "Y", flag_bacini_medi: "Y", flag_bacini_grandi: "N", lista_bacini_piccoli: "", lista_bacini_medi: "", lista_bacini_grandi: ""};
infoComuni["BADALUCCO"] = {classificazione: "INTERNO", zona: "A", flag_bacini_piccoli: "Y", flag_bacini_medi: "Y", flag_bacini_grandi: "N", lista_bacini_piccoli: "", lista_bacini_medi: "", lista_bacini_grandi: ""};
infoComuni["BAIARDO"] = {classificazione: "INTERNO", zona: "A", flag_bacini_piccoli: "Y", flag_bacini_medi: "N", flag_bacini_grandi: "N", lista_bacini_piccoli: "", lista_bacini_medi: "", lista_bacini_grandi: ""};
infoComuni["BORDIGHERA"] = {classificazione: "COSTIERO", zona: "A", flag_bacini_piccoli: "Y", flag_bacini_medi: "N", flag_bacini_grandi: "N", lista_bacini_piccoli: "", lista_bacini_medi: "", lista_bacini_grandi: ""};
infoComuni["BORGHETTO DI ARROSCIA"] = {classificazione: "INTERNO", zona: "A", flag_bacini_piccoli: "Y", flag_bacini_medi: "Y", flag_bacini_grandi: "Y", lista_bacini_piccoli: "", lista_bacini_medi: "", lista_bacini_grandi: "ARROSCIA"};
infoComuni["BORGOMARO"] = {classificazione: "INTERNO", zona: "A", flag_bacini_piccoli: "Y", flag_bacini_medi: "Y", flag_bacini_grandi: "N", lista_bacini_piccoli: "", lista_bacini_medi: "", lista_bacini_grandi: ""};
infoComuni["CAMPOROSSO"] = {classificazione: "COSTIERO", zona: "A", flag_bacini_piccoli: "Y", flag_bacini_medi: "N", flag_bacini_grandi: "Y", lista_bacini_piccoli: "", lista_bacini_medi: "", lista_bacini_grandi: "NERVIA"};
infoComuni["CARAVONICA"] = {classificazione: "INTERNO", zona: "A", flag_bacini_piccoli: "Y", flag_bacini_medi: "N", flag_bacini_grandi: "N", lista_bacini_piccoli: "", lista_bacini_medi: "", lista_bacini_grandi: ""};
infoComuni["CARPASIO"] = {classificazione: "INTERNO", zona: "A", flag_bacini_piccoli: "Y", flag_bacini_medi: "N", flag_bacini_grandi: "N", lista_bacini_piccoli: "", lista_bacini_medi: "", lista_bacini_grandi: ""};
infoComuni["CASTELLARO"] = {classificazione: "INTERNO", zona: "A", flag_bacini_piccoli: "Y", flag_bacini_medi: "N", flag_bacini_grandi: "N", lista_bacini_piccoli: "", lista_bacini_medi: "", lista_bacini_grandi: ""};
infoComuni["CASTEL VITTORIO"] = {classificazione: "INTERNO", zona: "A", flag_bacini_piccoli: "Y", flag_bacini_medi: "Y", flag_bacini_grandi: "N", lista_bacini_piccoli: "", lista_bacini_medi: "", lista_bacini_grandi: ""};
infoComuni["CERIANA"] = {classificazione: "INTERNO", zona: "A", flag_bacini_piccoli: "Y", flag_bacini_medi: "Y", flag_bacini_grandi: "N", lista_bacini_piccoli: "", lista_bacini_medi: "", lista_bacini_grandi: ""};
infoComuni["CERVO"] = {classificazione: "COSTIERO", zona: "A", flag_bacini_piccoli: "Y", flag_bacini_medi: "Y", flag_bacini_grandi: "N", lista_bacini_piccoli: "", lista_bacini_medi: "", lista_bacini_grandi: ""};
infoComuni["CESIO"] = {classificazione: "INTERNO", zona: "A", flag_bacini_piccoli: "Y", flag_bacini_medi: "N", flag_bacini_grandi: "N", lista_bacini_piccoli: "", lista_bacini_medi: "", lista_bacini_grandi: ""};
infoComuni["CHIUSANICO"] = {classificazione: "INTERNO", zona: "A", flag_bacini_piccoli: "Y", flag_bacini_medi: "Y", flag_bacini_grandi: "N", lista_bacini_piccoli: "", lista_bacini_medi: "", lista_bacini_grandi: ""};
infoComuni["CHIUSAVECCHIA"] = {classificazione: "INTERNO", zona: "A", flag_bacini_piccoli: "Y", flag_bacini_medi: "Y", flag_bacini_grandi: "N", lista_bacini_piccoli: "", lista_bacini_medi: "", lista_bacini_grandi: ""};
infoComuni["CIPRESSA"] = {classificazione: "COSTIERO", zona: "A", flag_bacini_piccoli: "Y", flag_bacini_medi: "Y", flag_bacini_grandi: "N", lista_bacini_piccoli: "", lista_bacini_medi: "", lista_bacini_grandi: ""};
infoComuni["CIVEZZA"] = {classificazione: "INTERNO", zona: "A", flag_bacini_piccoli: "Y", flag_bacini_medi: "Y", flag_bacini_grandi: "N", lista_bacini_piccoli: "", lista_bacini_medi: "", lista_bacini_grandi: ""};
infoComuni["COSIO DI ARROSCIA"] = {classificazione: "INTERNO", zona: "A", flag_bacini_piccoli: "Y", flag_bacini_medi: "Y", flag_bacini_grandi: "N", lista_bacini_piccoli: "", lista_bacini_medi: "", lista_bacini_grandi: ""};
infoComuni["COSTARAINERA"] = {classificazione: "COSTIERO", zona: "A", flag_bacini_piccoli: "Y", flag_bacini_medi: "N", flag_bacini_grandi: "N", lista_bacini_piccoli: "", lista_bacini_medi: "", lista_bacini_grandi: ""};
infoComuni["DIANO ARENTINO"] = {classificazione: "INTERNO", zona: "A", flag_bacini_piccoli: "Y", flag_bacini_medi: "N", flag_bacini_grandi: "N", lista_bacini_piccoli: "", lista_bacini_medi: "", lista_bacini_grandi: ""};
infoComuni["DIANO CASTELLO"] = {classificazione: "INTERNO", zona: "A", flag_bacini_piccoli: "Y", flag_bacini_medi: "Y", flag_bacini_grandi: "N", lista_bacini_piccoli: "", lista_bacini_medi: "", lista_bacini_grandi: ""};
infoComuni["DIANO MARINA"] = {classificazione: "COSTIERO", zona: "A", flag_bacini_piccoli: "Y", flag_bacini_medi: "Y", flag_bacini_grandi: "N", lista_bacini_piccoli: "", lista_bacini_medi: "", lista_bacini_grandi: ""};
infoComuni["DIANO SAN PIETRO"] = {classificazione: "INTERNO", zona: "A", flag_bacini_piccoli: "Y", flag_bacini_medi: "Y", flag_bacini_grandi: "N", lista_bacini_piccoli: "", lista_bacini_medi: "", lista_bacini_grandi: ""};
infoComuni["DOLCEACQUA"] = {classificazione: "INTERNO", zona: "A", flag_bacini_piccoli: "Y", flag_bacini_medi: "Y", flag_bacini_grandi: "Y", lista_bacini_piccoli: "", lista_bacini_medi: "", lista_bacini_grandi: "NERVIA"};
infoComuni["DOLCEDO"] = {classificazione: "INTERNO", zona: "A", flag_bacini_piccoli: "Y", flag_bacini_medi: "Y", flag_bacini_grandi: "N", lista_bacini_piccoli: "", lista_bacini_medi: "", lista_bacini_grandi: ""};
infoComuni["IMPERIA"] = {classificazione: "COSTIERO", zona: "A", flag_bacini_piccoli: "Y", flag_bacini_medi: "Y", flag_bacini_grandi: "N", lista_bacini_piccoli: "", lista_bacini_medi: "", lista_bacini_grandi: ""};
infoComuni["ISOLABONA"] = {classificazione: "INTERNO", zona: "A", flag_bacini_piccoli: "Y", flag_bacini_medi: "Y", flag_bacini_grandi: "N", lista_bacini_piccoli: "", lista_bacini_medi: "", lista_bacini_grandi: ""};
infoComuni["LUCINASCO"] = {classificazione: "INTERNO", zona: "A", flag_bacini_piccoli: "Y", flag_bacini_medi: "Y", flag_bacini_grandi: "N", lista_bacini_piccoli: "", lista_bacini_medi: "", lista_bacini_grandi: ""};
infoComuni["MENDATICA"] = {classificazione: "INTERNO", zona: "A", flag_bacini_piccoli: "Y", flag_bacini_medi: "N", flag_bacini_grandi: "N", lista_bacini_piccoli: "", lista_bacini_medi: "", lista_bacini_grandi: ""};
infoComuni["MOLINI DI TRIORA"] = {classificazione: "INTERNO", zona: "A", flag_bacini_piccoli: "Y", flag_bacini_medi: "Y", flag_bacini_grandi: "N", lista_bacini_piccoli: "", lista_bacini_medi: "", lista_bacini_grandi: ""};
infoComuni["MONTALTO LIGURE"] = {classificazione: "INTERNO", zona: "A", flag_bacini_piccoli: "Y", flag_bacini_medi: "Y", flag_bacini_grandi: "N", lista_bacini_piccoli: "", lista_bacini_medi: "", lista_bacini_grandi: ""};
infoComuni["MONTEGROSSO PIAN LATTE"] = {classificazione: "INTERNO", zona: "A", flag_bacini_piccoli: "Y", flag_bacini_medi: "Y", flag_bacini_grandi: "N", lista_bacini_piccoli: "", lista_bacini_medi: "", lista_bacini_grandi: ""};
infoComuni["OLIVETTA SAN MICHELE"] = {classificazione: "INTERNO", zona: "A", flag_bacini_piccoli: "Y", flag_bacini_medi: "Y", flag_bacini_grandi: "Y", lista_bacini_piccoli: "", lista_bacini_medi: "", lista_bacini_grandi: "ROJA"};
infoComuni["OSPEDALETTI"] = {classificazione: "COSTIERO", zona: "A", flag_bacini_piccoli: "Y", flag_bacini_medi: "N", flag_bacini_grandi: "N", lista_bacini_piccoli: "", lista_bacini_medi: "", lista_bacini_grandi: ""};
infoComuni["PERINALDO"] = {classificazione: "INTERNO", zona: "A", flag_bacini_piccoli: "Y", flag_bacini_medi: "N", flag_bacini_grandi: "N", lista_bacini_piccoli: "", lista_bacini_medi: "", lista_bacini_grandi: ""};
infoComuni["PIETRABRUNA"] = {classificazione: "INTERNO", zona: "A", flag_bacini_piccoli: "Y", flag_bacini_medi: "Y", flag_bacini_grandi: "N", lista_bacini_piccoli: "", lista_bacini_medi: "", lista_bacini_grandi: ""};
infoComuni["PIEVE DI TECO"] = {classificazione: "INTERNO", zona: "A", flag_bacini_piccoli: "Y", flag_bacini_medi: "Y", flag_bacini_grandi: "N", lista_bacini_piccoli: "", lista_bacini_medi: "", lista_bacini_grandi: ""};
infoComuni["PIGNA"] = {classificazione: "INTERNO", zona: "A", flag_bacini_piccoli: "Y", flag_bacini_medi: "Y", flag_bacini_grandi: "N", lista_bacini_piccoli: "", lista_bacini_medi: "", lista_bacini_grandi: ""};
infoComuni["POMPEIANA"] = {classificazione: "INTERNO", zona: "A", flag_bacini_piccoli: "Y", flag_bacini_medi: "N", flag_bacini_grandi: "N", lista_bacini_piccoli: "", lista_bacini_medi: "", lista_bacini_grandi: ""};
infoComuni["PONTEDASSIO"] = {classificazione: "INTERNO", zona: "A", flag_bacini_piccoli: "Y", flag_bacini_medi: "Y", flag_bacini_grandi: "N", lista_bacini_piccoli: "", lista_bacini_medi: "", lista_bacini_grandi: ""};
infoComuni["PORNASSIO"] = {classificazione: "INTERNO", zona: "A", flag_bacini_piccoli: "Y", flag_bacini_medi: "Y", flag_bacini_grandi: "N", lista_bacini_piccoli: "", lista_bacini_medi: "", lista_bacini_grandi: ""};
infoComuni["PRELA"] = {classificazione: "INTERNO", zona: "A", flag_bacini_piccoli: "Y", flag_bacini_medi: "Y", flag_bacini_grandi: "N", lista_bacini_piccoli: "", lista_bacini_medi: "", lista_bacini_grandi: ""};
infoComuni["RANZO"] = {classificazione: "INTERNO", zona: "A", flag_bacini_piccoli: "Y", flag_bacini_medi: "Y", flag_bacini_grandi: "Y", lista_bacini_piccoli: "", lista_bacini_medi: "", lista_bacini_grandi: "ARROSCIA"};
infoComuni["REZZO"] = {classificazione: "INTERNO", zona: "A", flag_bacini_piccoli: "Y", flag_bacini_medi: "Y", flag_bacini_grandi: "N", lista_bacini_piccoli: "", lista_bacini_medi: "", lista_bacini_grandi: ""};
infoComuni["RIVA LIGURE"] = {classificazione: "COSTIERO", zona: "A", flag_bacini_piccoli: "Y", flag_bacini_medi: "N", flag_bacini_grandi: "Y", lista_bacini_piccoli: "", lista_bacini_medi: "", lista_bacini_grandi: "ARGENTINA"};
infoComuni["ROCCHETTA NERVINA"] = {classificazione: "INTERNO", zona: "A", flag_bacini_piccoli: "Y", flag_bacini_medi: "Y", flag_bacini_grandi: "N", lista_bacini_piccoli: "", lista_bacini_medi: "", lista_bacini_grandi: ""};
infoComuni["SAN BARTOLOMEO AL MARE"] = {classificazione: "COSTIERO", zona: "A", flag_bacini_piccoli: "Y", flag_bacini_medi: "Y", flag_bacini_grandi: "N", lista_bacini_piccoli: "", lista_bacini_medi: "", lista_bacini_grandi: ""};
infoComuni["SAN BIAGIO DELLA CIMA"] = {classificazione: "INTERNO", zona: "A", flag_bacini_piccoli: "Y", flag_bacini_medi: "Y", flag_bacini_grandi: "N", lista_bacini_piccoli: "", lista_bacini_medi: "", lista_bacini_grandi: ""};
infoComuni["SAN LORENZO AL MARE"] = {classificazione: "COSTIERO", zona: "A", flag_bacini_piccoli: "Y", flag_bacini_medi: "Y", flag_bacini_grandi: "N", lista_bacini_piccoli: "", lista_bacini_medi: "", lista_bacini_grandi: ""};
infoComuni["SAN REMO"] = {classificazione: "COSTIERO", zona: "A", flag_bacini_piccoli: "Y", flag_bacini_medi: "Y", flag_bacini_grandi: "N", lista_bacini_piccoli: "", lista_bacini_medi: "", lista_bacini_grandi: ""};
infoComuni["SANTO STEFANO AL MARE"] = {classificazione: "COSTIERO", zona: "A", flag_bacini_piccoli: "Y", flag_bacini_medi: "N", flag_bacini_grandi: "N", lista_bacini_piccoli: "", lista_bacini_medi: "", lista_bacini_grandi: ""};
infoComuni["SEBORGA"] = {classificazione: "INTERNO", zona: "A", flag_bacini_piccoli: "Y", flag_bacini_medi: "N", flag_bacini_grandi: "N", lista_bacini_piccoli: "", lista_bacini_medi: "", lista_bacini_grandi: ""};
infoComuni["SOLDANO"] = {classificazione: "INTERNO", zona: "A", flag_bacini_piccoli: "Y", flag_bacini_medi: "N", flag_bacini_grandi: "N", lista_bacini_piccoli: "", lista_bacini_medi: "", lista_bacini_grandi: ""};
infoComuni["TAGGIA"] = {classificazione: "COSTIERO", zona: "A", flag_bacini_piccoli: "Y", flag_bacini_medi: "Y", flag_bacini_grandi: "Y", lista_bacini_piccoli: "", lista_bacini_medi: "", lista_bacini_grandi: "ARGENTINA"};
infoComuni["TERZORIO"] = {classificazione: "INTERNO", zona: "A", flag_bacini_piccoli: "Y", flag_bacini_medi: "N", flag_bacini_grandi: "N", lista_bacini_piccoli: "", lista_bacini_medi: "", lista_bacini_grandi: ""};
infoComuni["TRIORA"] = {classificazione: "INTERNO", zona: "A", flag_bacini_piccoli: "Y", flag_bacini_medi: "Y", flag_bacini_grandi: "N", lista_bacini_piccoli: "", lista_bacini_medi: "", lista_bacini_grandi: ""};
infoComuni["VALLEBONA"] = {classificazione: "INTERNO", zona: "A", flag_bacini_piccoli: "Y", flag_bacini_medi: "N", flag_bacini_grandi: "N", lista_bacini_piccoli: "", lista_bacini_medi: "", lista_bacini_grandi: ""};
infoComuni["VALLECROSIA"] = {classificazione: "COSTIERO", zona: "A", flag_bacini_piccoli: "Y", flag_bacini_medi: "Y", flag_bacini_grandi: "N", lista_bacini_piccoli: "", lista_bacini_medi: "", lista_bacini_grandi: ""};
infoComuni["VASIA"] = {classificazione: "INTERNO", zona: "A", flag_bacini_piccoli: "Y", flag_bacini_medi: "N", flag_bacini_grandi: "N", lista_bacini_piccoli: "", lista_bacini_medi: "", lista_bacini_grandi: ""};
infoComuni["VENTIMIGLIA"] = {classificazione: "COSTIERO", zona: "A", flag_bacini_piccoli: "Y", flag_bacini_medi: "Y", flag_bacini_grandi: "Y", lista_bacini_piccoli: "", lista_bacini_medi: "", lista_bacini_grandi: "ROJA - NERVIA - BEVERA"};
infoComuni["VESSALICO"] = {classificazione: "INTERNO", zona: "A", flag_bacini_piccoli: "Y", flag_bacini_medi: "Y", flag_bacini_grandi: "N", lista_bacini_piccoli: "", lista_bacini_medi: "", lista_bacini_grandi: ""};
infoComuni["VILLA FARALDI"] = {classificazione: "INTERNO", zona: "A", flag_bacini_piccoli: "Y", flag_bacini_medi: "N", flag_bacini_grandi: "N", lista_bacini_piccoli: "", lista_bacini_medi: "", lista_bacini_grandi: ""};
infoComuni["ALASSIO"] = {classificazione: "COSTIERO", zona: "A", flag_bacini_piccoli: "Y", flag_bacini_medi: "N", flag_bacini_grandi: "N", lista_bacini_piccoli: "", lista_bacini_medi: "", lista_bacini_grandi: ""};
infoComuni["ALBENGA"] = {classificazione: "COSTIERO", zona: "A", flag_bacini_piccoli: "Y", flag_bacini_medi: "Y", flag_bacini_grandi: "Y", lista_bacini_piccoli: "", lista_bacini_medi: "", lista_bacini_grandi: "CENTA - ARROSCIA"};
infoComuni["ALBISSOLA MARINA"] = {classificazione: "COSTIERO", zona: "B", flag_bacini_piccoli: "Y", flag_bacini_medi: "Y", flag_bacini_grandi: "N", lista_bacini_piccoli: "", lista_bacini_medi: "", lista_bacini_grandi: ""};
infoComuni["ALBISOLA SUPERIORE"] = {classificazione: "COSTIERO", zona: "B", flag_bacini_piccoli: "Y", flag_bacini_medi: "Y", flag_bacini_grandi: "N", lista_bacini_piccoli: "", lista_bacini_medi: "", lista_bacini_grandi: ""};
infoComuni["ALTARE"] = {classificazione: "INTERNO", zona: "D", flag_bacini_piccoli: "Y", flag_bacini_medi: "Y", flag_bacini_grandi: "N", lista_bacini_piccoli: "", lista_bacini_medi: "", lista_bacini_grandi: ""};
infoComuni["ANDORA"] = {classificazione: "COSTIERO", zona: "A", flag_bacini_piccoli: "Y", flag_bacini_medi: "Y", flag_bacini_grandi: "N", lista_bacini_piccoli: "", lista_bacini_medi: "", lista_bacini_grandi: ""};
infoComuni["ARNASCO"] = {classificazione: "INTERNO", zona: "A", flag_bacini_piccoli: "Y", flag_bacini_medi: "Y", flag_bacini_grandi: "N", lista_bacini_piccoli: "", lista_bacini_medi: "", lista_bacini_grandi: ""};
infoComuni["BALESTRINO"] = {classificazione: "INTERNO", zona: "A", flag_bacini_piccoli: "Y", flag_bacini_medi: "N", flag_bacini_grandi: "N", lista_bacini_piccoli: "", lista_bacini_medi: "", lista_bacini_grandi: ""};
infoComuni["BARDINETO"] = {classificazione: "INTERNO", zona: "D", flag_bacini_piccoli: "Y", flag_bacini_medi: "Y", flag_bacini_grandi: "N", lista_bacini_piccoli: "", lista_bacini_medi: "", lista_bacini_grandi: ""};
infoComuni["BERGEGGI"] = {classificazione: "COSTIERO", zona: "B", flag_bacini_piccoli: "Y", flag_bacini_medi: "N", flag_bacini_grandi: "N", lista_bacini_piccoli: "", lista_bacini_medi: "", lista_bacini_grandi: ""};
infoComuni["BOISSANO"] = {classificazione: "INTERNO", zona: "A", flag_bacini_piccoli: "Y", flag_bacini_medi: "N", flag_bacini_grandi: "N", lista_bacini_piccoli: "", lista_bacini_medi: "", lista_bacini_grandi: ""};
infoComuni["BORGHETTO SANTO SPIRITO"] = {classificazione: "COSTIERO", zona: "A", flag_bacini_piccoli: "Y", flag_bacini_medi: "Y", flag_bacini_grandi: "N", lista_bacini_piccoli: "", lista_bacini_medi: "", lista_bacini_grandi: ""};
infoComuni["BORGIO VEREZZI"] = {classificazione: "COSTIERO", zona: "A", flag_bacini_piccoli: "Y", flag_bacini_medi: "N", flag_bacini_grandi: "N", lista_bacini_piccoli: "", lista_bacini_medi: "", lista_bacini_grandi: ""};
infoComuni["BORMIDA"] = {classificazione: "INTERNO", zona: "D", flag_bacini_piccoli: "Y", flag_bacini_medi: "Y", flag_bacini_grandi: "N", lista_bacini_piccoli: "", lista_bacini_medi: "", lista_bacini_grandi: ""};
infoComuni["CAIRO MONTENOTTE"] = {classificazione: "INTERNO", zona: "D", flag_bacini_piccoli: "Y", flag_bacini_medi: "Y", flag_bacini_grandi: "Y", lista_bacini_piccoli: "", lista_bacini_medi: "", lista_bacini_grandi: "BORMIDA SPIGNO"};
infoComuni["CALICE LIGURE"] = {classificazione: "INTERNO", zona: "A", flag_bacini_piccoli: "Y", flag_bacini_medi: "Y", flag_bacini_grandi: "N", lista_bacini_piccoli: "", lista_bacini_medi: "", lista_bacini_grandi: ""};
infoComuni["CALIZZANO"] = {classificazione: "INTERNO", zona: "D", flag_bacini_piccoli: "Y", flag_bacini_medi: "Y", flag_bacini_grandi: "N", lista_bacini_piccoli: "", lista_bacini_medi: "", lista_bacini_grandi: ""};
infoComuni["CARCARE"] = {classificazione: "INTERNO", zona: "D", flag_bacini_piccoli: "Y", flag_bacini_medi: "Y", flag_bacini_grandi: "N", lista_bacini_piccoli: "", lista_bacini_medi: "", lista_bacini_grandi: ""};
infoComuni["CASANOVA LERRONE"] = {classificazione: "INTERNO", zona: "A", flag_bacini_piccoli: "Y", flag_bacini_medi: "Y", flag_bacini_grandi: "Y", lista_bacini_piccoli: "", lista_bacini_medi: "", lista_bacini_grandi: "ARROSCIA"};
infoComuni["CASTELBIANCO"] = {classificazione: "INTERNO", zona: "A", flag_bacini_piccoli: "Y", flag_bacini_medi: "Y", flag_bacini_grandi: "N", lista_bacini_piccoli: "", lista_bacini_medi: "", lista_bacini_grandi: ""};
infoComuni["CASTELVECCHIO DI ROCCA BARBENA"] = {classificazione: "INTERNO", zona: "A", flag_bacini_piccoli: "Y", flag_bacini_medi: "Y", flag_bacini_grandi: "N", lista_bacini_piccoli: "", lista_bacini_medi: "", lista_bacini_grandi: ""};
infoComuni["CELLE LIGURE"] = {classificazione: "COSTIERO", zona: "B", flag_bacini_piccoli: "Y", flag_bacini_medi: "N", flag_bacini_grandi: "N", lista_bacini_piccoli: "", lista_bacini_medi: "", lista_bacini_grandi: ""};
infoComuni["CENGIO"] = {classificazione: "INTERNO", zona: "D", flag_bacini_piccoli: "Y", flag_bacini_medi: "N", flag_bacini_grandi: "Y", lista_bacini_piccoli: "", lista_bacini_medi: "", lista_bacini_grandi: "BORMIDA MILLESIMO"};
infoComuni["CERIALE"] = {classificazione: "COSTIERO", zona: "A", flag_bacini_piccoli: "Y", flag_bacini_medi: "N", flag_bacini_grandi: "N", lista_bacini_piccoli: "", lista_bacini_medi: "", lista_bacini_grandi: ""};
infoComuni["CISANO SUL NEVA"] = {classificazione: "INTERNO", zona: "A", flag_bacini_piccoli: "Y", flag_bacini_medi: "Y", flag_bacini_grandi: "N", lista_bacini_piccoli: "", lista_bacini_medi: "", lista_bacini_grandi: ""};
infoComuni["COSSERIA"] = {classificazione: "INTERNO", zona: "D", flag_bacini_piccoli: "Y", flag_bacini_medi: "N", flag_bacini_grandi: "N", lista_bacini_piccoli: "", lista_bacini_medi: "", lista_bacini_grandi: ""};
infoComuni["DEGO"] = {classificazione: "INTERNO", zona: "D", flag_bacini_piccoli: "Y", flag_bacini_medi: "Y", flag_bacini_grandi: "Y", lista_bacini_piccoli: "", lista_bacini_medi: "", lista_bacini_grandi: "BORMIDA SPIGNO"};
infoComuni["ERLI"] = {classificazione: "INTERNO", zona: "A", flag_bacini_piccoli: "Y", flag_bacini_medi: "Y", flag_bacini_grandi: "N", lista_bacini_piccoli: "", lista_bacini_medi: "", lista_bacini_grandi: ""};
infoComuni["FINALE LIGURE"] = {classificazione: "COSTIERO", zona: "A", flag_bacini_piccoli: "Y", flag_bacini_medi: "Y", flag_bacini_grandi: "N", lista_bacini_piccoli: "", lista_bacini_medi: "", lista_bacini_grandi: ""};
infoComuni["GARLENDA"] = {classificazione: "INTERNO", zona: "A", flag_bacini_piccoli: "Y", flag_bacini_medi: "Y", flag_bacini_grandi: "N", lista_bacini_piccoli: "", lista_bacini_medi: "", lista_bacini_grandi: ""};
infoComuni["GIUSTENICE"] = {classificazione: "INTERNO", zona: "A", flag_bacini_piccoli: "Y", flag_bacini_medi: "Y", flag_bacini_grandi: "N", lista_bacini_piccoli: "", lista_bacini_medi: "", lista_bacini_grandi: ""};
infoComuni["GIUSVALLA"] = {classificazione: "INTERNO", zona: "D", flag_bacini_piccoli: "Y", flag_bacini_medi: "Y", flag_bacini_grandi: "N", lista_bacini_piccoli: "", lista_bacini_medi: "", lista_bacini_grandi: ""};
infoComuni["LAIGUEGLIA"] = {classificazione: "COSTIERO", zona: "A", flag_bacini_piccoli: "Y", flag_bacini_medi: "N", flag_bacini_grandi: "N", lista_bacini_piccoli: "", lista_bacini_medi: "", lista_bacini_grandi: ""};
infoComuni["LOANO"] = {classificazione: "COSTIERO", zona: "A", flag_bacini_piccoli: "Y", flag_bacini_medi: "N", flag_bacini_grandi: "N", lista_bacini_piccoli: "", lista_bacini_medi: "", lista_bacini_grandi: ""};
infoComuni["MAGLIOLO"] = {classificazione: "INTERNO", zona: "A", flag_bacini_piccoli: "Y", flag_bacini_medi: "Y", flag_bacini_grandi: "N", lista_bacini_piccoli: "", lista_bacini_medi: "", lista_bacini_grandi: ""};
infoComuni["MALLARE"] = {classificazione: "INTERNO", zona: "D", flag_bacini_piccoli: "Y", flag_bacini_medi: "Y", flag_bacini_grandi: "N", lista_bacini_piccoli: "", lista_bacini_medi: "", lista_bacini_grandi: ""};
infoComuni["MASSIMINO"] = {classificazione: "INTERNO", zona: "D", flag_bacini_piccoli: "Y", flag_bacini_medi: "N", flag_bacini_grandi: "N", lista_bacini_piccoli: "", lista_bacini_medi: "", lista_bacini_grandi: ""};
infoComuni["MILLESIMO"] = {classificazione: "INTERNO", zona: "D", flag_bacini_piccoli: "Y", flag_bacini_medi: "Y", flag_bacini_grandi: "Y", lista_bacini_piccoli: "", lista_bacini_medi: "", lista_bacini_grandi: "BORMIDA MILLESIMO"};
infoComuni["MIOGLIA"] = {classificazione: "INTERNO", zona: "D", flag_bacini_piccoli: "Y", flag_bacini_medi: "Y", flag_bacini_grandi: "N", lista_bacini_piccoli: "", lista_bacini_medi: "", lista_bacini_grandi: ""};
infoComuni["MURIALDO"] = {classificazione: "INTERNO", zona: "D", flag_bacini_piccoli: "Y", flag_bacini_medi: "Y", flag_bacini_grandi: "N", lista_bacini_piccoli: "", lista_bacini_medi: "", lista_bacini_grandi: ""};
infoComuni["NASINO"] = {classificazione: "INTERNO", zona: "A", flag_bacini_piccoli: "Y", flag_bacini_medi: "Y", flag_bacini_grandi: "N", lista_bacini_piccoli: "", lista_bacini_medi: "", lista_bacini_grandi: ""};
infoComuni["NOLI"] = {classificazione: "COSTIERO", zona: "A", flag_bacini_piccoli: "Y", flag_bacini_medi: "N", flag_bacini_grandi: "N", lista_bacini_piccoli: "", lista_bacini_medi: "", lista_bacini_grandi: ""};
infoComuni["ONZO"] = {classificazione: "INTERNO", zona: "A", flag_bacini_piccoli: "Y", flag_bacini_medi: "N", flag_bacini_grandi: "N", lista_bacini_piccoli: "", lista_bacini_medi: "", lista_bacini_grandi: ""};
infoComuni["ORCO FEGLINO"] = {classificazione: "INTERNO", zona: "A", flag_bacini_piccoli: "Y", flag_bacini_medi: "Y", flag_bacini_grandi: "N", lista_bacini_piccoli: "", lista_bacini_medi: "", lista_bacini_grandi: ""};
infoComuni["ORTOVERO"] = {classificazione: "INTERNO", zona: "A", flag_bacini_piccoli: "Y", flag_bacini_medi: "N", flag_bacini_grandi: "Y", lista_bacini_piccoli: "", lista_bacini_medi: "", lista_bacini_grandi: "ARROSCIA"};
infoComuni["OSIGLIA"] = {classificazione: "INTERNO", zona: "D", flag_bacini_piccoli: "Y", flag_bacini_medi: "Y", flag_bacini_grandi: "N", lista_bacini_piccoli: "", lista_bacini_medi: "", lista_bacini_grandi: ""};
infoComuni["PALLARE"] = {classificazione: "INTERNO", zona: "D", flag_bacini_piccoli: "Y", flag_bacini_medi: "Y", flag_bacini_grandi: "N", lista_bacini_piccoli: "", lista_bacini_medi: "", lista_bacini_grandi: ""};
infoComuni["PIANA CRIXIA"] = {classificazione: "INTERNO", zona: "D", flag_bacini_piccoli: "Y", flag_bacini_medi: "Y", flag_bacini_grandi: "Y", lista_bacini_piccoli: "", lista_bacini_medi: "", lista_bacini_grandi: "BORMIDA SPIGNO"};
infoComuni["PIETRA LIGURE"] = {classificazione: "COSTIERO", zona: "A", flag_bacini_piccoli: "Y", flag_bacini_medi: "Y", flag_bacini_grandi: "N", lista_bacini_piccoli: "", lista_bacini_medi: "", lista_bacini_grandi: ""};
infoComuni["PLODIO"] = {classificazione: "INTERNO", zona: "D", flag_bacini_piccoli: "Y", flag_bacini_medi: "N", flag_bacini_grandi: "N", lista_bacini_piccoli: "", lista_bacini_medi: "", lista_bacini_grandi: ""};
infoComuni["PONTINVREA"] = {classificazione: "INTERNO", zona: "D", flag_bacini_piccoli: "Y", flag_bacini_medi: "Y", flag_bacini_grandi: "N", lista_bacini_piccoli: "", lista_bacini_medi: "", lista_bacini_grandi: ""};
infoComuni["QUILIANO"] = {classificazione: "INTERNO", zona: "B", flag_bacini_piccoli: "Y", flag_bacini_medi: "Y", flag_bacini_grandi: "N", lista_bacini_piccoli: "", lista_bacini_medi: "", lista_bacini_grandi: ""};
infoComuni["RIALTO"] = {classificazione: "INTERNO", zona: "A", flag_bacini_piccoli: "Y", flag_bacini_medi: "Y", flag_bacini_grandi: "N", lista_bacini_piccoli: "", lista_bacini_medi: "", lista_bacini_grandi: ""};
infoComuni["ROCCAVIGNALE"] = {classificazione: "INTERNO", zona: "D", flag_bacini_piccoli: "Y", flag_bacini_medi: "Y", flag_bacini_grandi: "Y", lista_bacini_piccoli: "", lista_bacini_medi: "", lista_bacini_grandi: "BORMIDA MILLESIMO"};
infoComuni["SASSELLO"] = {classificazione: "INTERNO", zona: "D", flag_bacini_piccoli: "Y", flag_bacini_medi: "Y", flag_bacini_grandi: "N", lista_bacini_piccoli: "", lista_bacini_medi: "", lista_bacini_grandi: ""};
infoComuni["SAVONA"] = {classificazione: "COSTIERO", zona: "B", flag_bacini_piccoli: "Y", flag_bacini_medi: "Y", flag_bacini_grandi: "N", lista_bacini_piccoli: "", lista_bacini_medi: "", lista_bacini_grandi: ""};
infoComuni["SPOTORNO"] = {classificazione: "COSTIERO", zona: "B", flag_bacini_piccoli: "Y", flag_bacini_medi: "N", flag_bacini_grandi: "N", lista_bacini_piccoli: "", lista_bacini_medi: "", lista_bacini_grandi: ""};
infoComuni["STELLA"] = {classificazione: "INTERNO", zona: "B", flag_bacini_piccoli: "Y", flag_bacini_medi: "Y", flag_bacini_grandi: "N", lista_bacini_piccoli: "", lista_bacini_medi: "", lista_bacini_grandi: ""};
infoComuni["STELLANELLO"] = {classificazione: "INTERNO", zona: "A", flag_bacini_piccoli: "Y", flag_bacini_medi: "Y", flag_bacini_grandi: "N", lista_bacini_piccoli: "", lista_bacini_medi: "", lista_bacini_grandi: ""};
infoComuni["TESTICO"] = {classificazione: "INTERNO", zona: "A", flag_bacini_piccoli: "Y", flag_bacini_medi: "Y", flag_bacini_grandi: "N", lista_bacini_piccoli: "", lista_bacini_medi: "", lista_bacini_grandi: ""};
infoComuni["TOIRANO"] = {classificazione: "INTERNO", zona: "A", flag_bacini_piccoli: "Y", flag_bacini_medi: "Y", flag_bacini_grandi: "N", lista_bacini_piccoli: "", lista_bacini_medi: "", lista_bacini_grandi: ""};
infoComuni["TOVO SAN GIACOMO"] = {classificazione: "INTERNO", zona: "A", flag_bacini_piccoli: "Y", flag_bacini_medi: "Y", flag_bacini_grandi: "N", lista_bacini_piccoli: "", lista_bacini_medi: "", lista_bacini_grandi: ""};
infoComuni["URBE"] = {classificazione: "INTERNO", zona: "D", flag_bacini_piccoli: "Y", flag_bacini_medi: "Y", flag_bacini_grandi: "N", lista_bacini_piccoli: "", lista_bacini_medi: "", lista_bacini_grandi: ""};
infoComuni["VADO LIGURE"] = {classificazione: "COSTIERO", zona: "B", flag_bacini_piccoli: "Y", flag_bacini_medi: "Y", flag_bacini_grandi: "N", lista_bacini_piccoli: "", lista_bacini_medi: "", lista_bacini_grandi: ""};
infoComuni["VARAZZE"] = {classificazione: "COSTIERO", zona: "B", flag_bacini_piccoli: "Y", flag_bacini_medi: "Y", flag_bacini_grandi: "N", lista_bacini_piccoli: "", lista_bacini_medi: "", lista_bacini_grandi: ""};
infoComuni["VENDONE"] = {classificazione: "INTERNO", zona: "A", flag_bacini_piccoli: "Y", flag_bacini_medi: "N", flag_bacini_grandi: "N", lista_bacini_piccoli: "", lista_bacini_medi: "", lista_bacini_grandi: ""};
infoComuni["VEZZI PORTIO"] = {classificazione: "INTERNO", zona: "A", flag_bacini_piccoli: "Y", flag_bacini_medi: "N", flag_bacini_grandi: "N", lista_bacini_piccoli: "", lista_bacini_medi: "", lista_bacini_grandi: ""};
infoComuni["VILLANOVA DI ALBENGA"] = {classificazione: "INTERNO", zona: "A", flag_bacini_piccoli: "Y", flag_bacini_medi: "Y", flag_bacini_grandi: "Y", lista_bacini_piccoli: "", lista_bacini_medi: "", lista_bacini_grandi: "ARROSCIA"};
infoComuni["ZUCCARELLO"] = {classificazione: "INTERNO", zona: "A", flag_bacini_piccoli: "Y", flag_bacini_medi: "Y", flag_bacini_grandi: "N", lista_bacini_piccoli: "", lista_bacini_medi: "", lista_bacini_grandi: ""};
infoComuni["ARENZANO"] = {classificazione: "COSTIERO", zona: "B", flag_bacini_piccoli: "Y", flag_bacini_medi: "Y", flag_bacini_grandi: "N", lista_bacini_piccoli: "", lista_bacini_medi: "", lista_bacini_grandi: ""};
infoComuni["AVEGNO"] = {classificazione: "INTERNO", zona: "B", flag_bacini_piccoli: "Y", flag_bacini_medi: "N", flag_bacini_grandi: "N", lista_bacini_piccoli: "", lista_bacini_medi: "", lista_bacini_grandi: ""};
infoComuni["BARGAGLI"] = {classificazione: "INTERNO", zona: "B", flag_bacini_piccoli: "Y", flag_bacini_medi: "Y", flag_bacini_grandi: "N", lista_bacini_piccoli: "", lista_bacini_medi: "", lista_bacini_grandi: ""};
infoComuni["BOGLIASCO"] = {classificazione: "COSTIERO", zona: "B", flag_bacini_piccoli: "Y", flag_bacini_medi: "N", flag_bacini_grandi: "N", lista_bacini_piccoli: "", lista_bacini_medi: "", lista_bacini_grandi: ""};
infoComuni["BORZONASCA"] = {classificazione: "INTERNO", zona: "C", flag_bacini_piccoli: "Y", flag_bacini_medi: "Y", flag_bacini_grandi: "N", lista_bacini_piccoli: "", lista_bacini_medi: "", lista_bacini_grandi: ""};
infoComuni["BUSALLA"] = {classificazione: "INTERNO", zona: "E", flag_bacini_piccoli: "Y", flag_bacini_medi: "Y", flag_bacini_grandi: "Y", lista_bacini_piccoli: "", lista_bacini_medi: "", lista_bacini_grandi: "SCRIVIA"};
infoComuni["CAMOGLI"] = {classificazione: "COSTIERO", zona: "B", flag_bacini_piccoli: "Y", flag_bacini_medi: "N", flag_bacini_grandi: "N", lista_bacini_piccoli: "", lista_bacini_medi: "", lista_bacini_grandi: ""};
infoComuni["CAMPO LIGURE"] = {classificazione: "INTERNO", zona: "D", flag_bacini_piccoli: "Y", flag_bacini_medi: "Y", flag_bacini_grandi: "N", lista_bacini_piccoli: "", lista_bacini_medi: "", lista_bacini_grandi: ""};
infoComuni["CAMPOMORONE"] = {classificazione: "INTERNO", zona: "B", flag_bacini_piccoli: "Y", flag_bacini_medi: "Y", flag_bacini_grandi: "N", lista_bacini_piccoli: "", lista_bacini_medi: "", lista_bacini_grandi: ""};
infoComuni["CARASCO"] = {classificazione: "INTERNO", zona: "C", flag_bacini_piccoli: "Y", flag_bacini_medi: "Y", flag_bacini_grandi: "Y", lista_bacini_piccoli: "", lista_bacini_medi: "", lista_bacini_grandi: "LAVAGNA - ENTELLA"};
infoComuni["CASARZA LIGURE"] = {classificazione: "INTERNO", zona: "C", flag_bacini_piccoli: "Y", flag_bacini_medi: "Y", flag_bacini_grandi: "N", lista_bacini_piccoli: "", lista_bacini_medi: "", lista_bacini_grandi: ""};
infoComuni["CASELLA"] = {classificazione: "INTERNO", zona: "E", flag_bacini_piccoli: "Y", flag_bacini_medi: "Y", flag_bacini_grandi: "N", lista_bacini_piccoli: "", lista_bacini_medi: "", lista_bacini_grandi: ""};
infoComuni["CASTIGLIONE CHIAVARESE"] = {classificazione: "INTERNO", zona: "C", flag_bacini_piccoli: "Y", flag_bacini_medi: "Y", flag_bacini_grandi: "N", lista_bacini_piccoli: "", lista_bacini_medi: "", lista_bacini_grandi: ""};
infoComuni["CERANESI"] = {classificazione: "INTERNO", zona: "B", flag_bacini_piccoli: "Y", flag_bacini_medi: "Y", flag_bacini_grandi: "N", lista_bacini_piccoli: "", lista_bacini_medi: "", lista_bacini_grandi: ""};
infoComuni["CHIAVARI"] = {classificazione: "COSTIERO", zona: "C", flag_bacini_piccoli: "Y", flag_bacini_medi: "N", flag_bacini_grandi: "Y", lista_bacini_piccoli: "", lista_bacini_medi: "", lista_bacini_grandi: "ENTELLA"};
infoComuni["CICAGNA"] = {classificazione: "INTERNO", zona: "C", flag_bacini_piccoli: "Y", flag_bacini_medi: "Y", flag_bacini_grandi: "N", lista_bacini_piccoli: "", lista_bacini_medi: "", lista_bacini_grandi: ""};
infoComuni["COGOLETO"] = {classificazione: "COSTIERO", zona: "B", flag_bacini_piccoli: "Y", flag_bacini_medi: "Y", flag_bacini_grandi: "N", lista_bacini_piccoli: "", lista_bacini_medi: "", lista_bacini_grandi: ""};
infoComuni["COGORNO"] = {classificazione: "INTERNO", zona: "C", flag_bacini_piccoli: "Y", flag_bacini_medi: "Y", flag_bacini_grandi: "Y", lista_bacini_piccoli: "", lista_bacini_medi: "", lista_bacini_grandi: "ENTELLA"};
infoComuni["COREGLIA LIGURE"] = {classificazione: "INTERNO", zona: "C", flag_bacini_piccoli: "Y", flag_bacini_medi: "Y", flag_bacini_grandi: "N", lista_bacini_piccoli: "", lista_bacini_medi: "", lista_bacini_grandi: ""};
infoComuni["CROCEFIESCHI"] = {classificazione: "INTERNO", zona: "E", flag_bacini_piccoli: "Y", flag_bacini_medi: "Y", flag_bacini_grandi: "N", lista_bacini_piccoli: "", lista_bacini_medi: "", lista_bacini_grandi: ""};
infoComuni["DAVAGNA"] = {classificazione: "INTERNO", zona: "B", flag_bacini_piccoli: "Y", flag_bacini_medi: "Y", flag_bacini_grandi: "N", lista_bacini_piccoli: "", lista_bacini_medi: "", lista_bacini_grandi: ""};
infoComuni["FASCIA"] = {classificazione: "INTERNO", zona: "E", flag_bacini_piccoli: "Y", flag_bacini_medi: "Y", flag_bacini_grandi: "N", lista_bacini_piccoli: "", lista_bacini_medi: "", lista_bacini_grandi: ""};
infoComuni["FAVALE DI MALVARO"] = {classificazione: "INTERNO", zona: "C", flag_bacini_piccoli: "Y", flag_bacini_medi: "N", flag_bacini_grandi: "N", lista_bacini_piccoli: "", lista_bacini_medi: "", lista_bacini_grandi: ""};
infoComuni["FONTANIGORDA"] = {classificazione: "INTERNO", zona: "E", flag_bacini_piccoli: "Y", flag_bacini_medi: "Y", flag_bacini_grandi: "N", lista_bacini_piccoli: "", lista_bacini_medi: "", lista_bacini_grandi: ""};
infoComuni["GENOVA"] = {classificazione: "COSTIERO", zona: "B", flag_bacini_piccoli: "Y", flag_bacini_medi: "Y", flag_bacini_grandi: "N", lista_bacini_piccoli: "", lista_bacini_medi: "", lista_bacini_grandi: ""};
infoComuni["GORRETO"] = {classificazione: "INTERNO", zona: "E", flag_bacini_piccoli: "Y", flag_bacini_medi: "Y", flag_bacini_grandi: "Y", lista_bacini_piccoli: "", lista_bacini_medi: "", lista_bacini_grandi: "TREBBIA"};
infoComuni["ISOLA DEL CANTONE"] = {classificazione: "INTERNO", zona: "E", flag_bacini_piccoli: "Y", flag_bacini_medi: "Y", flag_bacini_grandi: "Y", lista_bacini_piccoli: "", lista_bacini_medi: "", lista_bacini_grandi: "SCRIVIA"};
infoComuni["LAVAGNA"] = {classificazione: "COSTIERO", zona: "C", flag_bacini_piccoli: "Y", flag_bacini_medi: "N", flag_bacini_grandi: "Y", lista_bacini_piccoli: "", lista_bacini_medi: "", lista_bacini_grandi: "ENTELLA"};
infoComuni["LEIVI"] = {classificazione: "INTERNO", zona: "C", flag_bacini_piccoli: "Y", flag_bacini_medi: "Y", flag_bacini_grandi: "Y", lista_bacini_piccoli: "", lista_bacini_medi: "", lista_bacini_grandi: "LAVAGNA"};
infoComuni["LORSICA"] = {classificazione: "INTERNO", zona: "C", flag_bacini_piccoli: "Y", flag_bacini_medi: "Y", flag_bacini_grandi: "N", lista_bacini_piccoli: "", lista_bacini_medi: "", lista_bacini_grandi: ""};
infoComuni["LUMARZO"] = {classificazione: "INTERNO", zona: "C", flag_bacini_piccoli: "Y", flag_bacini_medi: "Y", flag_bacini_grandi: "N", lista_bacini_piccoli: "", lista_bacini_medi: "", lista_bacini_grandi: ""};
infoComuni["MASONE"] = {classificazione: "INTERNO", zona: "D", flag_bacini_piccoli: "Y", flag_bacini_medi: "Y", flag_bacini_grandi: "N", lista_bacini_piccoli: "", lista_bacini_medi: "", lista_bacini_grandi: ""};
infoComuni["MELE"] = {classificazione: "INTERNO", zona: "B", flag_bacini_piccoli: "Y", flag_bacini_medi: "N", flag_bacini_grandi: "N", lista_bacini_piccoli: "", lista_bacini_medi: "", lista_bacini_grandi: ""};
infoComuni["MEZZANEGO"] = {classificazione: "INTERNO", zona: "C", flag_bacini_piccoli: "Y", flag_bacini_medi: "Y", flag_bacini_grandi: "N", lista_bacini_piccoli: "", lista_bacini_medi: "", lista_bacini_grandi: ""};
infoComuni["MIGNANEGO"] = {classificazione: "INTERNO", zona: "B", flag_bacini_piccoli: "Y", flag_bacini_medi: "N", flag_bacini_grandi: "N", lista_bacini_piccoli: "", lista_bacini_medi: "", lista_bacini_grandi: ""};
infoComuni["MOCONESI"] = {classificazione: "INTERNO", zona: "C", flag_bacini_piccoli: "Y", flag_bacini_medi: "Y", flag_bacini_grandi: "N", lista_bacini_piccoli: "", lista_bacini_medi: "", lista_bacini_grandi: ""};
infoComuni["MONEGLIA"] = {classificazione: "COSTIERO", zona: "C", flag_bacini_piccoli: "Y", flag_bacini_medi: "N", flag_bacini_grandi: "N", lista_bacini_piccoli: "", lista_bacini_medi: "", lista_bacini_grandi: ""};
infoComuni["MONTEBRUNO"] = {classificazione: "INTERNO", zona: "E", flag_bacini_piccoli: "Y", flag_bacini_medi: "Y", flag_bacini_grandi: "N", lista_bacini_piccoli: "", lista_bacini_medi: "", lista_bacini_grandi: ""};
infoComuni["MONTOGGIO"] = {classificazione: "INTERNO", zona: "E", flag_bacini_piccoli: "Y", flag_bacini_medi: "Y", flag_bacini_grandi: "N", lista_bacini_piccoli: "", lista_bacini_medi: "", lista_bacini_grandi: ""};
infoComuni["NE"] = {classificazione: "INTERNO", zona: "C", flag_bacini_piccoli: "Y", flag_bacini_medi: "Y", flag_bacini_grandi: "N", lista_bacini_piccoli: "", lista_bacini_medi: "", lista_bacini_grandi: ""};
infoComuni["NEIRONE"] = {classificazione: "INTERNO", zona: "C", flag_bacini_piccoli: "Y", flag_bacini_medi: "Y", flag_bacini_grandi: "N", lista_bacini_piccoli: "", lista_bacini_medi: "", lista_bacini_grandi: ""};
infoComuni["ORERO"] = {classificazione: "INTERNO", zona: "C", flag_bacini_piccoli: "Y", flag_bacini_medi: "Y", flag_bacini_grandi: "N", lista_bacini_piccoli: "", lista_bacini_medi: "", lista_bacini_grandi: ""};
infoComuni["PIEVE LIGURE"] = {classificazione: "COSTIERO", zona: "B", flag_bacini_piccoli: "Y", flag_bacini_medi: "N", flag_bacini_grandi: "N", lista_bacini_piccoli: "", lista_bacini_medi: "", lista_bacini_grandi: ""};
infoComuni["PORTOFINO"] = {classificazione: "COSTIERO", zona: "C", flag_bacini_piccoli: "Y", flag_bacini_medi: "N", flag_bacini_grandi: "N", lista_bacini_piccoli: "", lista_bacini_medi: "", lista_bacini_grandi: ""};
infoComuni["PROPATA"] = {classificazione: "INTERNO", zona: "E", flag_bacini_piccoli: "Y", flag_bacini_medi: "Y", flag_bacini_grandi: "N", lista_bacini_piccoli: "", lista_bacini_medi: "", lista_bacini_grandi: ""};
infoComuni["RAPALLO"] = {classificazione: "COSTIERO", zona: "C", flag_bacini_piccoli: "Y", flag_bacini_medi: "Y", flag_bacini_grandi: "N", lista_bacini_piccoli: "", lista_bacini_medi: "", lista_bacini_grandi: ""};
infoComuni["RECCO"] = {classificazione: "COSTIERO", zona: "B", flag_bacini_piccoli: "Y", flag_bacini_medi: "Y", flag_bacini_grandi: "N", lista_bacini_piccoli: "", lista_bacini_medi: "", lista_bacini_grandi: ""};
infoComuni["REZZOAGLIO"] = {classificazione: "INTERNO", zona: "E", flag_bacini_piccoli: "Y", flag_bacini_medi: "Y", flag_bacini_grandi: "Y", lista_bacini_piccoli: "", lista_bacini_medi: "", lista_bacini_grandi: "AVETO"};
infoComuni["RONCO SCRIVIA"] = {classificazione: "INTERNO", zona: "E", flag_bacini_piccoli: "Y", flag_bacini_medi: "Y", flag_bacini_grandi: "Y", lista_bacini_piccoli: "", lista_bacini_medi: "", lista_bacini_grandi: "SCRIVIA"};
infoComuni["RONDANINA"] = {classificazione: "INTERNO", zona: "E", flag_bacini_piccoli: "Y", flag_bacini_medi: "Y", flag_bacini_grandi: "N", lista_bacini_piccoli: "", lista_bacini_medi: "", lista_bacini_grandi: ""};
infoComuni["ROSSIGLIONE"] = {classificazione: "INTERNO", zona: "D", flag_bacini_piccoli: "Y", flag_bacini_medi: "Y", flag_bacini_grandi: "N", lista_bacini_piccoli: "", lista_bacini_medi: "", lista_bacini_grandi: ""};
infoComuni["ROVEGNO"] = {classificazione: "INTERNO", zona: "E", flag_bacini_piccoli: "Y", flag_bacini_medi: "Y", flag_bacini_grandi: "Y", lista_bacini_piccoli: "", lista_bacini_medi: "", lista_bacini_grandi: "TREBBIA"};
infoComuni["SAN COLOMBANO CERTENOLI"] = {classificazione: "INTERNO", zona: "C", flag_bacini_piccoli: "Y", flag_bacini_medi: "Y", flag_bacini_grandi: "Y", lista_bacini_piccoli: "", lista_bacini_medi: "", lista_bacini_grandi: "LAVAGNA"};
infoComuni["SANTA MARGHERITA LIGURE"] = {classificazione: "COSTIERO", zona: "C", flag_bacini_piccoli: "Y", flag_bacini_medi: "N", flag_bacini_grandi: "N", lista_bacini_piccoli: "", lista_bacini_medi: "", lista_bacini_grandi: ""};
infoComuni["SANTO OLCESE"] = {classificazione: "INTERNO", zona: "B", flag_bacini_piccoli: "Y", flag_bacini_medi: "Y", flag_bacini_grandi: "N", lista_bacini_piccoli: "", lista_bacini_medi: "", lista_bacini_grandi: ""};
infoComuni["SANTO STEFANO D AVETO"] = {classificazione: "INTERNO", zona: "E", flag_bacini_piccoli: "Y", flag_bacini_medi: "Y", flag_bacini_grandi: "Y", lista_bacini_piccoli: "", lista_bacini_medi: "", lista_bacini_grandi: "AVETO"};
infoComuni["SAVIGNONE"] = {classificazione: "INTERNO", zona: "E", flag_bacini_piccoli: "Y", flag_bacini_medi: "Y", flag_bacini_grandi: "N", lista_bacini_piccoli: "", lista_bacini_medi: "", lista_bacini_grandi: ""};
infoComuni["SERRA RICCO"] = {classificazione: "INTERNO", zona: "B", flag_bacini_piccoli: "Y", flag_bacini_medi: "Y", flag_bacini_grandi: "N", lista_bacini_piccoli: "", lista_bacini_medi: "", lista_bacini_grandi: ""};
infoComuni["SESTRI LEVANTE"] = {classificazione: "COSTIERO", zona: "C", flag_bacini_piccoli: "Y", flag_bacini_medi: "Y", flag_bacini_grandi: "N", lista_bacini_piccoli: "", lista_bacini_medi: "", lista_bacini_grandi: ""};
infoComuni["SORI"] = {classificazione: "COSTIERO", zona: "B", flag_bacini_piccoli: "Y", flag_bacini_medi: "N", flag_bacini_grandi: "N", lista_bacini_piccoli: "", lista_bacini_medi: "", lista_bacini_grandi: ""};
infoComuni["TIGLIETO"] = {classificazione: "INTERNO", zona: "D", flag_bacini_piccoli: "Y", flag_bacini_medi: "Y", flag_bacini_grandi: "N", lista_bacini_piccoli: "", lista_bacini_medi: "", lista_bacini_grandi: ""};
infoComuni["TORRIGLIA"] = {classificazione: "INTERNO", zona: "E", flag_bacini_piccoli: "Y", flag_bacini_medi: "Y", flag_bacini_grandi: "N", lista_bacini_piccoli: "", lista_bacini_medi: "", lista_bacini_grandi: ""};
infoComuni["TRIBOGNA"] = {classificazione: "INTERNO", zona: "C", flag_bacini_piccoli: "Y", flag_bacini_medi: "Y", flag_bacini_grandi: "N", lista_bacini_piccoli: "", lista_bacini_medi: "", lista_bacini_grandi: ""};
infoComuni["USCIO"] = {classificazione: "INTERNO", zona: "C", flag_bacini_piccoli: "Y", flag_bacini_medi: "Y", flag_bacini_grandi: "N", lista_bacini_piccoli: "", lista_bacini_medi: "", lista_bacini_grandi: ""};
infoComuni["VALBREVENNA"] = {classificazione: "INTERNO", zona: "E", flag_bacini_piccoli: "Y", flag_bacini_medi: "Y", flag_bacini_grandi: "N", lista_bacini_piccoli: "", lista_bacini_medi: "", lista_bacini_grandi: ""};
infoComuni["VOBBIA"] = {classificazione: "INTERNO", zona: "E", flag_bacini_piccoli: "Y", flag_bacini_medi: "Y", flag_bacini_grandi: "N", lista_bacini_piccoli: "", lista_bacini_medi: "", lista_bacini_grandi: ""};
infoComuni["ZOAGLI"] = {classificazione: "COSTIERO", zona: "C", flag_bacini_piccoli: "Y", flag_bacini_medi: "N", flag_bacini_grandi: "N", lista_bacini_piccoli: "", lista_bacini_medi: "", lista_bacini_grandi: ""};
infoComuni["AMEGLIA"] = {classificazione: "COSTIERO", zona: "C", flag_bacini_piccoli: "Y", flag_bacini_medi: "N", flag_bacini_grandi: "Y", lista_bacini_piccoli: "", lista_bacini_medi: "", lista_bacini_grandi: "MAGRA"};
infoComuni["ARCOLA"] = {classificazione: "INTERNO", zona: "C", flag_bacini_piccoli: "Y", flag_bacini_medi: "N", flag_bacini_grandi: "Y", lista_bacini_piccoli: "", lista_bacini_medi: "", lista_bacini_grandi: "MAGRA"};
infoComuni["BEVERINO"] = {classificazione: "INTERNO", zona: "C", flag_bacini_piccoli: "Y", flag_bacini_medi: "Y", flag_bacini_grandi: "Y", lista_bacini_piccoli: "", lista_bacini_medi: "", lista_bacini_grandi: "VARA"};
infoComuni["BOLANO"] = {classificazione: "INTERNO", zona: "C", flag_bacini_piccoli: "Y", flag_bacini_medi: "N", flag_bacini_grandi: "Y", lista_bacini_piccoli: "", lista_bacini_medi: "", lista_bacini_grandi: "VARA - MAGRA"};
infoComuni["BONASSOLA"] = {classificazione: "COSTIERO", zona: "C", flag_bacini_piccoli: "Y", flag_bacini_medi: "N", flag_bacini_grandi: "N", lista_bacini_piccoli: "", lista_bacini_medi: "", lista_bacini_grandi: ""};
infoComuni["BORGHETTO DI VARA"] = {classificazione: "INTERNO", zona: "C", flag_bacini_piccoli: "Y", flag_bacini_medi: "Y", flag_bacini_grandi: "Y", lista_bacini_piccoli: "", lista_bacini_medi: "", lista_bacini_grandi: "VARA"};
infoComuni["BRUGNATO"] = {classificazione: "INTERNO", zona: "C", flag_bacini_piccoli: "Y", flag_bacini_medi: "Y", flag_bacini_grandi: "Y", lista_bacini_piccoli: "", lista_bacini_medi: "", lista_bacini_grandi: "VARA"};
infoComuni["CALICE AL CORNOVIGLIO"] = {classificazione: "INTERNO", zona: "C", flag_bacini_piccoli: "Y", flag_bacini_medi: "Y", flag_bacini_grandi: "Y", lista_bacini_piccoli: "", lista_bacini_medi: "", lista_bacini_grandi: "VARA"};
infoComuni["CARRO"] = {classificazione: "INTERNO", zona: "C", flag_bacini_piccoli: "Y", flag_bacini_medi: "Y", flag_bacini_grandi: "Y", lista_bacini_piccoli: "", lista_bacini_medi: "", lista_bacini_grandi: "VARA"};
infoComuni["CARRODANO"] = {classificazione: "INTERNO", zona: "C", flag_bacini_piccoli: "Y", flag_bacini_medi: "Y", flag_bacini_grandi: "Y", lista_bacini_piccoli: "", lista_bacini_medi: "", lista_bacini_grandi: "VARA"};
infoComuni["CASTELNUOVO MAGRA"] = {classificazione: "INTERNO", zona: "C", flag_bacini_piccoli: "Y", flag_bacini_medi: "Y", flag_bacini_grandi: "N", lista_bacini_piccoli: "", lista_bacini_medi: "", lista_bacini_grandi: ""};
infoComuni["DEIVA MARINA"] = {classificazione: "COSTIERO", zona: "C", flag_bacini_piccoli: "Y", flag_bacini_medi: "N", flag_bacini_grandi: "N", lista_bacini_piccoli: "", lista_bacini_medi: "", lista_bacini_grandi: ""};
infoComuni["FOLLO"] = {classificazione: "INTERNO", zona: "C", flag_bacini_piccoli: "Y", flag_bacini_medi: "N", flag_bacini_grandi: "Y", lista_bacini_piccoli: "", lista_bacini_medi: "", lista_bacini_grandi: "VARA"};
infoComuni["FRAMURA"] = {classificazione: "COSTIERO", zona: "C", flag_bacini_piccoli: "Y", flag_bacini_medi: "Y", flag_bacini_grandi: "N", lista_bacini_piccoli: "", lista_bacini_medi: "", lista_bacini_grandi: ""};
infoComuni["LA SPEZIA"] = {classificazione: "COSTIERO", zona: "C", flag_bacini_piccoli: "Y", flag_bacini_medi: "N", flag_bacini_grandi: "N", lista_bacini_piccoli: "", lista_bacini_medi: "", lista_bacini_grandi: ""};
infoComuni["LERICI"] = {classificazione: "COSTIERO", zona: "C", flag_bacini_piccoli: "Y", flag_bacini_medi: "N", flag_bacini_grandi: "Y", lista_bacini_piccoli: "", lista_bacini_medi: "", lista_bacini_grandi: "MAGRA"};
infoComuni["LEVANTO"] = {classificazione: "COSTIERO", zona: "C", flag_bacini_piccoli: "Y", flag_bacini_medi: "N", flag_bacini_grandi: "N", lista_bacini_piccoli: "", lista_bacini_medi: "", lista_bacini_grandi: ""};
infoComuni["MAISSANA"] = {classificazione: "INTERNO", zona: "C", flag_bacini_piccoli: "Y", flag_bacini_medi: "Y", flag_bacini_grandi: "N", lista_bacini_piccoli: "", lista_bacini_medi: "", lista_bacini_grandi: ""};
infoComuni["MONTEROSSO AL MARE"] = {classificazione: "COSTIERO", zona: "C", flag_bacini_piccoli: "Y", flag_bacini_medi: "N", flag_bacini_grandi: "N", lista_bacini_piccoli: "", lista_bacini_medi: "", lista_bacini_grandi: ""};
infoComuni["ORTONOVO"] = {classificazione: "COSTIERO", zona: "C", flag_bacini_piccoli: "Y", flag_bacini_medi: "Y", flag_bacini_grandi: "N", lista_bacini_piccoli: "", lista_bacini_medi: "", lista_bacini_grandi: ""};
infoComuni["PIGNONE"] = {classificazione: "INTERNO", zona: "C", flag_bacini_piccoli: "Y", flag_bacini_medi: "Y", flag_bacini_grandi: "N", lista_bacini_piccoli: "", lista_bacini_medi: "", lista_bacini_grandi: ""};
infoComuni["PORTOVENERE"] = {classificazione: "COSTIERO", zona: "C", flag_bacini_piccoli: "Y", flag_bacini_medi: "N", flag_bacini_grandi: "N", lista_bacini_piccoli: "", lista_bacini_medi: "", lista_bacini_grandi: ""};
infoComuni["RICCO DEL GOLFO DI SPEZIA"] = {classificazione: "INTERNO", zona: "C", flag_bacini_piccoli: "Y", flag_bacini_medi: "Y", flag_bacini_grandi: "N", lista_bacini_piccoli: "", lista_bacini_medi: "", lista_bacini_grandi: ""};
infoComuni["RIOMAGGIORE"] = {classificazione: "COSTIERO", zona: "C", flag_bacini_piccoli: "Y", flag_bacini_medi: "N", flag_bacini_grandi: "N", lista_bacini_piccoli: "", lista_bacini_medi: "", lista_bacini_grandi: ""};
infoComuni["ROCCHETTA DI VARA"] = {classificazione: "INTERNO", zona: "C", flag_bacini_piccoli: "Y", flag_bacini_medi: "Y", flag_bacini_grandi: "Y", lista_bacini_piccoli: "", lista_bacini_medi: "", lista_bacini_grandi: "VARA"};
infoComuni["SANTO STEFANO DI MAGRA"] = {classificazione: "INTERNO", zona: "C", flag_bacini_piccoli: "Y", flag_bacini_medi: "Y", flag_bacini_grandi: "Y", lista_bacini_piccoli: "", lista_bacini_medi: "", lista_bacini_grandi: "MAGRA"};
infoComuni["SARZANA"] = {classificazione: "COSTIERO", zona: "C", flag_bacini_piccoli: "Y", flag_bacini_medi: "Y", flag_bacini_grandi: "Y", lista_bacini_piccoli: "", lista_bacini_medi: "", lista_bacini_grandi: "MAGRA"};
infoComuni["SESTA GODANO"] = {classificazione: "INTERNO", zona: "C", flag_bacini_piccoli: "Y", flag_bacini_medi: "Y", flag_bacini_grandi: "Y", lista_bacini_piccoli: "", lista_bacini_medi: "", lista_bacini_grandi: "VARA"};
infoComuni["VARESE LIGURE"] = {classificazione: "INTERNO", zona: "C", flag_bacini_piccoli: "Y", flag_bacini_medi: "Y", flag_bacini_grandi: "Y", lista_bacini_piccoli: "", lista_bacini_medi: "", lista_bacini_grandi: "VARA"};
infoComuni["VERNAZZA"] = {classificazione: "COSTIERO", zona: "C", flag_bacini_piccoli: "Y", flag_bacini_medi: "N", flag_bacini_grandi: "N", lista_bacini_piccoli: "", lista_bacini_medi: "", lista_bacini_grandi: ""};
infoComuni["VEZZANO LIGURE"] = {classificazione: "INTERNO", zona: "C", flag_bacini_piccoli: "Y", flag_bacini_medi: "N", flag_bacini_grandi: "Y", lista_bacini_piccoli: "", lista_bacini_medi: "", lista_bacini_grandi: "VARA - MAGRA"};
infoComuni["ZIGNAGO"] = {classificazione: "INTERNO", zona: "C", flag_bacini_piccoli: "Y", flag_bacini_medi: "Y", flag_bacini_grandi: "N", lista_bacini_piccoli: "", lista_bacini_medi: "", lista_bacini_grandi: ""};
        });
        
        $(function() {
            var listaComuniA = [];
            var listaComuniB = [];
            var listaComuniC = [];
            var listaComuniD = [];
            var listaComuniE = [];
            var index;

            for(index in infoComuni) {
                if(infoComuni[index].zona == "A") {
                    listaComuniA.push(index);
                }
                else if(infoComuni[index].zona == "B") {
                    listaComuniB.push(index);
                }
                else if(infoComuni[index].zona == "C") {
                    listaComuniC.push(index);
                }
                else if(infoComuni[index].zona == "D") {
                    listaComuniD.push(index);
                }
                else if(infoComuni[index].zona == "E") {
                    listaComuniE.push(index);
                }
            }

            $( "#comuni-bacini-zona-A" ).autocomplete({
                source: listaComuniA
            });
            $( "#comuni-bacini-zona-B" ).autocomplete({
                source: listaComuniB
            });
            $( "#comuni-bacini-zona-C" ).autocomplete({
                source: listaComuniC
            });
            $( "#comuni-bacini-zona-D" ).autocomplete({
                source: listaComuniD
            });
            $( "#comuni-bacini-zona-E" ).autocomplete({
                source: listaComuniE
            });

            $( "#comuni-cls-zona-A" ).autocomplete({
                source: listaComuniA
            });
            $( "#comuni-cls-zona-B" ).autocomplete({
                source: listaComuniB
            });
            $( "#comuni-cls-zona-C" ).autocomplete({
                source: listaComuniC
            });
            $( "#comuni-cls-zona-D" ).autocomplete({
                source: listaComuniD
            });
            $( "#comuni-cls-zona-E" ).autocomplete({
                source: listaComuniE
            });
        });

        $(function() {
            //init zona A
            $("#pnl-comune-bacini-zona-A").hide();
            $("#pnl-bacini-piccoli-zona-A").hide();
            $("#pnl-bacini-medi-zona-A").hide();
            $("#pnl-bacini-grandi-zona-A").hide();
            $("#pnl-comune-cls-zona-A").hide();
            $("#pnl-comune-cls-value-zona-A").hide();

            //init zona B
            $("#pnl-comune-bacini-zona-B").hide();
            $("#pnl-bacini-piccoli-zona-B").hide();
            $("#pnl-bacini-medi-zona-B").hide();
            $("#pnl-bacini-grandi-zona-B").hide();
            $("#pnl-comune-cls-zona-B").hide();
            $("#pnl-comune-cls-value-zona-B").hide();

            //init zona C
            $("#pnl-comune-bacini-zona-C").hide();
            $("#pnl-bacini-piccoli-zona-C").hide();
            $("#pnl-bacini-medi-zona-C").hide();
            $("#pnl-bacini-grandi-zona-C").hide();
            $("#pnl-comune-cls-zona-C").hide();
            $("#pnl-comune-cls-value-zona-C").hide();

            //init zona D
            $("#pnl-comune-bacini-zona-D").hide();
            $("#pnl-bacini-piccoli-zona-D").hide();
            $("#pnl-bacini-medi-zona-D").hide();
            $("#pnl-bacini-grandi-zona-D").hide();
            $("#pnl-comune-cls-zona-D").hide();
            $("#pnl-comune-cls-value-zona-D").hide();

            //init zona E
            $("#pnl-comune-bacini-zona-E").hide();
            $("#pnl-bacini-piccoli-zona-E").hide();
            $("#pnl-bacini-medi-zona-E").hide();
            $("#pnl-bacini-grandi-zona-E").hide();
            $("#pnl-comune-cls-zona-E").hide();
            $("#pnl-comune-cls-value-zona-E").hide();
        });

        function updateBaciniComuni(codZona) {
            $("#pnl-comune-bacini-zona-" + codZona).hide();
            $("#pnl-bacini-piccoli-zona-" + codZona).hide();
            $("#pnl-bacini-medi-zona-" + codZona).hide();
            $("#pnl-bacini-grandi-zona-" + codZona).hide();
            
            var txtComuneSelezionato = $("#comuni-bacini-zona-" + codZona).val().trim().toUpperCase();

            //gestione valore non trovato
            if(infoComuni[txtComuneSelezionato] == null) {
                //alert('non definito');
                $("#lbl-comune-bacini-zona-" + codZona).text("Comune non trovato.");
                $("#pnl-comune-bacini-zona-" + codZona).show();
                return false;
            }

            //aggiorno valori per il comune selezionato
            if(infoComuni[txtComuneSelezionato].flag_bacini_piccoli == "Y" ||
               infoComuni[txtComuneSelezionato].flag_bacini_medi == "Y" ||
               infoComuni[txtComuneSelezionato].flag_bacini_grandi == "Y")
            {
                $("#lbl-comune-bacini-zona-" + codZona).text(txtComuneSelezionato + " presenta:");
                $("#pnl-comune-bacini-zona-" + codZona).show();

                if(infoComuni[txtComuneSelezionato].flag_bacini_piccoli == "Y")
                {
                    $("#pnl-bacini-piccoli-zona-" + codZona).show();

                    if(infoComuni[txtComuneSelezionato].lista_bacini_piccoli.length > 0) {
                        $("#lbl-bacini-piccoli-zona-" + codZona).text(": " +
                            infoComuni[txtComuneSelezionato].lista_bacini_piccoli);
                    }

                }

                if(infoComuni[txtComuneSelezionato].flag_bacini_medi == "Y")
                {
                    $("#pnl-bacini-medi-zona-" + codZona).show();

                    if(infoComuni[txtComuneSelezionato].lista_bacini_medi.length > 0) {
                        $("#lbl-bacini-medi-zona-" + codZona).text(": " +
                            infoComuni[txtComuneSelezionato].lista_bacini_medi);
                    }
                    
                }

                if(infoComuni[txtComuneSelezionato].flag_bacini_grandi == "Y")
                {
                    $("#pnl-bacini-grandi-zona-" + codZona).show();

                    if(infoComuni[txtComuneSelezionato].lista_bacini_grandi.length > 0) {
                        $("#lbl-bacini-grandi-zona-" + codZona).text(": " +
                            infoComuni[txtComuneSelezionato].lista_bacini_grandi);
                    }
                }
            }
            else
            {
                $("#lbl-comune-bacini-zona-" + codZona).text(txtComuneSelezionato + " non presenta alcun bacino.");
                $("#pnl-comune-bacini-zona-" + codZona).show();
            }
        }

        function updateClassificazioneComuni(codZona) {
            $("#pnl-comune-cls-zona-" + codZona).hide();
            $("#pnl-comune-cls-value-zona-" + codZona).hide();
            
            var txtComuneSelezionato = $("#comuni-cls-zona-" + codZona).val().trim().toUpperCase();

            //gestione valore non trovato
            if(infoComuni[txtComuneSelezionato] == null) {
                //alert('non definito');
                $("#lbl-comune-cls-zona-" + codZona).text("Comune non trovato.");
                $("#pnl-comune-cls-zona-" + codZona).show();
                return false;
            }

            //aggiorno valori per il comune selezionato
            $("#lbl-comune-cls-zona-" + codZona).text(txtComuneSelezionato + ":");
            $("#pnl-comune-cls-zona-" + codZona).show();

            if(infoComuni[txtComuneSelezionato].classificazione == "INTERNO")
            {
                $("#lbl-comune-cls-value-zona-" + codZona).text("Comune interno");

            }
            else if(infoComuni[txtComuneSelezionato].classificazione == "COSTIERO")
            {
                $("#lbl-comune-cls-value-zona-" + codZona).text("Comune costiero");
            }

            $("#pnl-comune-cls-value-zona-" + codZona).show();
        }
        </script>
    </head>
    <body>

                
        <!-- Header -->
<section class="al-header hide-for-small">
    <div class="row">
        <div class="large-12 medium-12 columns">
            <div class="row">
                <div id="al-header-left" class="large-8 medium-7 columns">
                    <div id="al-logo-header-allerta-liguria">
                        <span style="color: #e00000">ALLERTA</span>
                        <span style="color: #565656">LIGURIA</span>
                        <br>
                        <span style="font-size: 17px; color: #565656">Sito ufficiale gestito da Regione Liguria e ARPAL</span>
                    </div>
                </div>
                <div id="al-header-right" class="large-4 medium-5 columns">
                    <div id="al-loghi-header" class="right">
                        <a href="http://www.arpal.gov.it" target="_blank"><div id="al-logo-header-arpal" class="right"><img src="img/loghi/logo_arpal_liguria.png" alt="ARPAL" title="Vai al sito ARPAL" /></div></a>
                        <a href="http://www.regione.liguria.it/uffici.html?id_dipartimento=10&amp;controller=contenutiufficio&amp;id_ufficio=34&amp;view=contenutiufficio" target="_blank"><div id="al-logo-header-protezione-civile" class="right"><img src="img/loghi/logo_protezione_civile.png" alt="Protezione Civile Regione Liguria" title="Vai al sito della Protezione Civile Regione Liguria" /></div></a>
                        <a href="http://www.regione.liguria.it" target="_blank"><div id="al-logo-header-regione-liguria" class="right"><img src="img/loghi/logo_regione_liguria.png" alt="Regione Liguria" title="Vai al sito della Regione Liguria" /></div></a>
                    </div>
                </div>
            </div>
        </div>
    </div>
</section>

<!-- Navigation bar -->
<section class="al-navbar">
    <div class="row collapse">
        <div class="small-12 columns">
            <div class="contain-to-grid sticky">

                <nav class="top-bar" data-topbar data-options="sticky_on: large" >
                    <ul class="title-area">
                        <li class="name">
                            <div class="row show-for-small">
                                <div class="small-12 columns">
                                    <div id="al-logo-header-allerta-liguria-small" class="al-container al-parent-centered" style="width: 100%; height: 100%">
                                        <div class="al-container al-child-centered">
                                            <span style="color: #e00000">ALLERTA</span>
                                            <span style="color: #333333">LIGURIA</span>
                                        </div>
                                    </div>
                                </div>
                            </div>
                        </li>
                        <!-- Remove the class "menu-icon" to get rid of menu icon. Take out "Menu" to just have icon alone -->
                        <li class="toggle-topbar menu-icon">
                            <a href="#"><span>Menu</span></a>
                        </li>
                    </ul>

                    <section class="top-bar-section">
                        <ul class="left">
                            <li class="divider"></li>
                            <li class="active">
                                <a href="index.php" class="">Homepage</a>
                            </li>
                            <li class="divider"></li>
                            <li class="has-dropdown not-click">
                                <a href="#" class="">Messaggi</a>
                                <ul class="dropdown">
                                    <li class="">
                                        <a href="allerta_protezione_civile.php">Allerta di Protezione Civile - Regione Liguria</a>
                                    </li>
                                    <li class="">
                                        <a href="bollettino_vigilanza_arpal.php">Bollettino di Vigilanza/Avviso meteo di ARPAL</a>
                                    </li>
                                    <li class="">
                                        <a href="criticita_idro_arpal.php">Messaggio/Avviso di Criticità Idrologica di ARPAL</a>
                                    </li>
                                    <li class="">
                                        <a href="messaggi_monitoraggio_arpal.php">Monitoraggio meteoidro di ARPAL</a>
                                    </li>
                                    <li class="">
                                        <a href="guida_lettura_messaggi.php">Guida alla lettura dei messaggi</a>
                                    </li>
                                    <li class="">
                                        <a href="social_network.php">Social network</a>
                                    </li>
                                </ul>
                            </li>
                            <li class="divider"></li>
                            <li class="">
                                <a href="dati_tempo_reale.php" class="">Dati in tempo reale</a>
                            </li>
                            <li class="divider"></li>
                            <li class="has-dropdown not-click">
                                <a href="#" class="">Guida all'allerta</a>
                                <ul class="dropdown">
                                    <li class="">
                                        <a href="protezione_civile.php">Il sistema di Protezione Civile: chi fa cosa</a>
                                    </li>
                                    <li class="">
                                        <a href="livelli_allerta_rischi.php">Livelli di Allerta e altri rischi</a>
                                    </li>
                                    <li class="">
                                        <a href="divisione_territorio.php">Divisione del territorio</a>
                                    </li>
                                </ul>
                            </li>
                            <li class="divider"></li>
                            <li class="">
                                <a href="misure_autoprotezione.php" class="">Misure di autoprotezione</a>
                            </li>
                            <li class="divider"></li>
                            <li class="">
                                <a href="link_utili.php" class="">Link utili</a>
                            </li>
                            <li class="divider"></li>
                            <li class="">
                                <a href="contatti.php" class="">Contatti</a>
                            </li>
                            <li class="divider"></li>
                        </ul>
                    </section>
                </nav>    
            </div>
        </div>
    </div>
</section>
<!-- News ticker bar -->

<section class="al-news-ticker-bar">
    <div class="row collapse">
        <div class="small-12 columns">
            <div class="al-news-ticker">
                                <ul style="display: none">
                    <li data-subcategory="SITUAZIONE IN ATTO" data-color="c0392b" >
                        <a href="#al-panel-monitoraggio">Vai alla sezione per vedere i dati in tempo reale</a>
                    </li>
                </ul>
            </div>
        </div>
    </div>
</section>
<!-- Message bar -->


<section class="al-background-white" style="margin-top: 15px">
    <div class="row">
        <a href="index.php">
            <div class="large-12 columns al-msgbar-green">
                <h2 class="al-text-no-underline al-text-horz-center al-text-normal">
                    Messaggio del 26/11/2016 ore 08:50                </h2>
                <h1 class="al-text-no-underline al-text-horz-center">Nessuna Allerta</h1>
                <h2 class="al-text-no-underline al-text-horz-center">Rischio meteo per vento</h2>
            </div>
        </a>
    </div>
</section>

        <section style="margin-top: 15px">
            <div class="row">
                <div class="large-6 medium-6 columns">
                    <div class="al-map-panel">
                        <div class="al-text-header al-background-gray">
                            <h1 class="al-color-verydarkgray">LIVELLI DI ALLERTA MASSIMI PER ZONA</h1>
                            <h3 class="al-color-verydarkgray">Seleziona la zona per validità, orari e dettagli</h3>
                        </div>
                        <div id="al-map-liguria-panel">
                            <div style="position: relative; max-width: 463px">
                                                                <img style="max-width: 100%; max-height: 100%" src="img/mappe/V_V_V_V_V.png"
                                     alt="LIVELLI DI ALLERTA MASSIMI - Seleziona la zona per validità e dettagli"
                                     title="LIVELLI DI ALLERTA MASSIMI - Seleziona la zona per validità e dettagli" />
                                <a href="#al-zona-A" onclick="activateAccordionElement('al-accordion-zone-elem-A')">
                                    <img style="position: absolute; width:9%; top: 78%; left: 12%" src="img/icone/label_zona_trasparente.png"
                                         alt="Zona A" title="Zona A" />
                                </a>
                                <a href="#al-zona-B" onclick="activateAccordionElement('al-accordion-zone-elem-B')">
                                    <img style="position: absolute; width:9%; top: 26%; left: 48%" src="img/icone/label_zona_trasparente.png"
                                         alt="Zona B" title="Zona B" />
                                </a>
                                <a href="#al-zona-C" onclick="activateAccordionElement('al-accordion-zone-elem-C')">
                                    <img style="position: absolute; width:9%; top: 47%; left: 78%" src="img/icone/label_zona_trasparente.png"
                                         alt="Zona C" title="Zona C" />
                                </a>
                                <a href="#al-zona-D" onclick="activateAccordionElement('al-accordion-zone-elem-D')">
                                    <img style="position: absolute; width:9%; top: 11%; left: 27%" src="img/icone/label_zona_trasparente.png"
                                         alt="Zona D" title="Zona D" />
                                </a>
                                <a href="#al-zona-E" onclick="activateAccordionElement('al-accordion-zone-elem-E')">
                                    <img style="position: absolute; width:9%; top: 0%; left: 62%" src="img/icone/label_zona_trasparente.png"
                                         alt="Zona E" title="Zona E" />
                                </a>
                                
                                                                <div id="al-label-container-mappa" class="al-container right al-position-absolute">
                                                                            <a href="#al-panel-monitoraggio" title="Vai alla sezione monitoraggio" class="al-component-hidden">
                                            <div id="al-label-monitoraggio">
                                                <h1 class="al-color-white al-text-horz-center">MONITORAGGIO IN CORSO</h1>
                                            </div>
                                        </a>
                                                                    </div>
                                                            </div>
                        </div>
                    </div>
                </div>
                <div class="large-6 medium-6 columns">
                    <div class="al-text-header al-background-gray hide-for-small">
                        <h1 class="al-color-verydarkgray">FENOMENI METEO SIGNIFICATIVI PREVISTI</h1>
                    </div>
                    <div class="row panel al-no-border al-no-padding al-background-white al-table-allerta-rischi-panel">

                        <!-- Contenitore responsive fenomeni meteo idrogeo e neve -->
                        <div class="large-7 medium-7 columns al-background-gray">

                            <!-- Tabella Allerta -->
                            <div class="row al-table-allerta-panel">
                                <div class="large-2 medium-3 small-2 columns">
                                    <div class="al-container">
                                        <div class="al-container-padded show-for-small">
                                            <div class="left al-table-column-header al-width-100-pct"></div>
                                        </div>
                                        <div class="al-container-padded">
                                            <div class="left al-table-column-header al-width-100-pct"></div>
                                        </div>
                                        <div class="al-container-padded">
                                            <a href="#al-zona-A" onclick="activateAccordionElement('al-accordion-zone-elem-A')"
                                               title="Zona A">
                                                <div class="left al-table-row-header al-width-100-pct">
                                                    <h4 class="al-color-verydarkgray">A</h4>
                                                </div>
                                            </a>
                                        </div>
                                        <div class="al-container-padded">
                                            <a href="#al-zona-B" onclick="activateAccordionElement('al-accordion-zone-elem-B')"
                                               title="Zona B">
                                                <div class="left al-table-row-header al-width-100-pct">
                                                    <h4 class="al-color-verydarkgray">B</h4>
                                                </div>
                                            </a>
                                        </div>
                                        <div class="al-container-padded">
                                            <a href="#al-zona-C" onclick="activateAccordionElement('al-accordion-zone-elem-C')"
                                               title="Zona C">
                                                <div class="left al-table-row-header al-width-100-pct">
                                                    <h4 class="al-color-verydarkgray">C</h4>
                                                </div>
                                            </a>
                                        </div>
                                        <div class="al-container-padded">
                                            <a href="#al-zona-D" onclick="activateAccordionElement('al-accordion-zone-elem-D')"
                                               title="Zona D">
                                                <div class="left al-table-row-header al-width-100-pct">
                                                    <h4 class="al-color-verydarkgray">D</h4>
                                                </div>
                                            </a>
                                        </div>
                                        <div class="al-container-padded">
                                            <a href="#al-zona-E" onclick="activateAccordionElement('al-accordion-zone-elem-E')"
                                               title="Zona E">
                                                <div class="left al-table-row-header al-width-100-pct">
                                                    <h4 class="al-color-verydarkgray">E</h4>
                                                </div>
                                            </a>
                                        </div>
                                    </div>
                                </div>
                                <div class="large-10 medium-9 small-10 columns">
                                    <div class="al-container">
                                        <div class="al-container-padded show-for-small">
                                            <div class="left al-table-column-header al-width-100-pct">
                                                <h2 class="al-color-verydarkgray">FENOMENI METEO SIGNIFICATIVI PREVISTI</h2>
                                            </div>
                                        </div>
                                        <div class="al-container-padded left al-width-33-pct">
                                            <div class="al-table-column-header">
                                                <h5 class="al-color-verydarkgray">PIOGGE<br>DIFFUSE</h5>
                                            </div>
                                        </div>
                                        <div class="al-container-padded left al-width-33-pct">
                                            <div class="al-table-column-header">
                                                <h5 class="al-color-verydarkgray">TEMPORALI</h5>
                                            </div>
                                        </div>
                                        <div class="al-container-padded right al-width-33-pct">
                                            <div class="al-table-column-header" style="padding-top: 3px">
                                                <h5 class="al-color-column">NEVE</h5>
                                            </div>
                                        </div>
                                    </div>

                                    <!-- Rischi meteo zona A -->
                                    <div class="al-container al-background-lightgray">
                                        <div class="al-container-padded left al-width-33-pct">
                                            <div class="al-table-cell al-background-white">
                                                                                            </div>
                                        </div>
                                        <div class="al-container-padded left al-width-33-pct">
                                            <div class="al-table-cell al-background-white">
                                                                                            </div>
                                        </div>
                                        <div class="al-container-padded right al-width-33-pct">
                                            <div class="al-table-cell al-background-white">
                                                                                            </div>
                                        </div>
                                    </div>

                                    <!-- Rischi meteo zona B -->
                                    <div class="al-container al-background-lightgray">
                                        <div class="al-container-padded left al-width-33-pct">
                                            <div class="al-table-cell al-background-white">
                                                                                            </div>
                                        </div>
                                        <div class="al-container-padded left al-width-33-pct">
                                            <div class="al-table-cell al-background-white">
                                                                                            </div>
                                        </div>
                                        <div class="al-container-padded right al-width-33-pct">
                                            <div class="al-table-cell al-background-white">
                                                                                            </div>
                                        </div>
                                    </div>

                                    <!-- Rischi meteo zona C -->
                                    <div class="al-container al-background-lightgray">
                                        <div class="al-container-padded left al-width-33-pct">
                                            <div class="al-table-cell al-background-white">
                                                                                            </div>
                                        </div>
                                        <div class="al-container-padded left al-width-33-pct">
                                            <div class="al-table-cell al-background-white">
                                                                                            </div>
                                        </div>
                                        <div class="al-container-padded right al-width-33-pct">
                                            <div class="al-table-cell al-background-white">
                                                                                            </div>
                                        </div>
                                    </div>

                                    <!-- Rischi meteo zona D -->
                                    <div class="al-container al-background-lightgray">
                                        <div class="al-container-padded left al-width-33-pct">
                                            <div class="al-table-cell al-background-white">
                                                                                            </div>
                                        </div>
                                        <div class="al-container-padded left al-width-33-pct">
                                            <div class="al-table-cell al-background-white">
                                                                                            </div>
                                        </div>
                                        <div class="al-container-padded right al-width-33-pct">
                                            <div class="al-table-cell al-background-white">
                                                                                            </div>
                                        </div>
                                    </div>

                                    <!-- Rischi meteo zona E -->
                                    <div class="al-container al-background-lightgray">
                                        <div class="al-container-padded left al-width-33-pct">
                                            <div class="al-table-cell al-background-white">
                                                                                            </div>
                                        </div>
                                        <div class="al-container-padded left al-width-33-pct">
                                            <div class="al-table-cell al-background-white">
                                                                                            </div>
                                        </div>
                                        <div class="al-container-padded right al-width-33-pct">
                                            <div class="al-table-cell al-background-white">
                                                                                            </div>
                                        </div>
                                    </div>
                                </div>
                            </div>
                            <div class="row show-for-small al-background-white" style="height: 20px"></div>
                        </div>

                        <!-- Contenitore responsive fenomeni meteo vento, mare e disagio fisiologico -->
                        <div class="large-5 medium-5 columns al-background-gray">

                            <!-- Tabella Rischi Meteo -->
                            <div class="row al-table-rischi-panel">

                                <!-- Tabella Rischi Meteo: colonna ZONE (si visualizza solo su risoluzioni small) -->
                                <div class="small-2 columns show-for-small">
                                    <div class="al-container">
                                        <div class="al-container-padded">
                                            <div class="left al-table-column-header al-width-100-pct show-for-small"></div>
                                        </div>
                                        <div class="al-container-padded">
                                            <div class="left al-table-column-header al-width-100-pct show-for-small"></div>
                                        </div>
                                        <div class="al-container-padded">
                                            <div class="left al-table-row-header al-width-100-pct show-for-small">
                                                <h4 class="al-color-verydarkgray">A</h4>
                                            </div>
                                        </div>
                                        <div class="al-container-padded">
                                            <div class="left al-table-row-header al-width-100-pct show-for-small">
                                                <h4 class="al-color-verydarkgray">B</h4>
                                            </div>
                                        </div>
                                        <div class="al-container-padded">
                                            <div class="left al-table-row-header al-width-100-pct show-for-small">
                                                <h4 class="al-color-verydarkgray">C</h4>
                                            </div>
                                        </div>
                                        <div class="al-container-padded">
                                            <div class="left al-table-row-header al-width-100-pct show-for-small">
                                                <h4 class="al-color-verydarkgray">D</h4>
                                            </div>
                                        </div>
                                        <div class="al-container-padded">
                                            <div class="left al-table-row-header al-width-100-pct show-for-small">
                                                <h4 class="al-color-verydarkgray">E</h4>
                                            </div>
                                        </div>
                                    </div>
                                </div>

                                <!-- Tabella Rischi Meteo: corpo tabella (prende tutta la larghezza del contenitore su dispositivi non small) -->
                                <div class="large-12 medium-12 small-10 columns">
                                    <div class="al-container">
                                        <div class="al-container-padded show-for-small">
                                            <div class="left al-table-column-header al-width-100-pct">
                                                <h2 class="al-color-verydarkgray">FENOMENI METEO SIGNIFICATIVI PREVISTI</h2>
                                            </div>
                                        </div>
                                        <div class="al-container-padded left al-width-33-pct">
                                            <div class="al-table-column-header">
                                                <h5 class="al-color-verydarkgray">VENTO</h5>
                                            </div>
                                        </div>
                                        <div class="al-container-padded left al-width-33-pct">
                                            <div class="al-table-column-header">
                                                <h5 class="al-color-verydarkgray">MARE</h5>
                                            </div>
                                        </div>
                                        <div class="al-container-padded right al-width-33-pct">
                                            <div class="al-table-column-header" style="padding-top: 3px">
                                                <h5 class="al-color-column">DISAGIO<br>FISIOL.</h5>
                                            </div>
                                        </div>
                                    </div>

                                    <!-- Rischi meteo zona A -->
                                    <div class="al-container al-background-lightgray">
                                        <div class="al-container-padded left al-width-33-pct">
                                            <div class="al-table-cell al-background-white">
                                                                                                    <img src="img/icone/spunta.png"
                                                         alt="Rischio vento" title="Rischio vento" />
                                                                                            </div>
                                        </div>
                                        <div class="al-container-padded left al-width-33-pct">
                                            <div class="al-table-cell al-background-white">
                                                                                            </div>
                                        </div>
                                        <div class="al-container-padded right al-width-33-pct">
                                            <div class="al-table-cell al-background-white">
                                                                                            </div>
                                        </div>
                                    </div>

                                    <!-- Rischi meteo zona B -->
                                    <div class="al-container al-background-lightgray">
                                        <div class="al-container-padded left al-width-33-pct">
                                            <div class="al-table-cell al-background-white">
                                                                                                    <img src="img/icone/spunta.png"
                                                         alt="Rischio vento" title="Rischio vento" />
                                                                                            </div>
                                        </div>
                                        <div class="al-container-padded left al-width-33-pct">
                                            <div class="al-table-cell al-background-white">
                                                                                            </div>
                                        </div>
                                        <div class="al-container-padded right al-width-33-pct">
                                            <div class="al-table-cell al-background-white">
                                                                                            </div>
                                        </div>
                                    </div>

                                    <!-- Rischi meteo zona C -->
                                    <div class="al-container al-background-lightgray">
                                        <div class="al-container-padded left al-width-33-pct">
                                            <div class="al-table-cell al-background-white">
                                                                                                    <img src="img/icone/spunta.png"
                                                         alt="Rischio vento" title="Rischio vento" />
                                                                                            </div>
                                        </div>
                                        <div class="al-container-padded left al-width-33-pct">
                                            <div class="al-table-cell al-background-white">
                                                                                            </div>
                                        </div>
                                        <div class="al-container-padded right al-width-33-pct">
                                            <div class="al-table-cell al-background-white">
                                                                                            </div>
                                        </div>
                                    </div>

                                    <!-- Rischi meteo zona D -->
                                    <div class="al-container al-background-lightgray">
                                        <div class="al-container-padded left al-width-33-pct">
                                            <div class="al-table-cell al-background-white">
                                                                                                    <img src="img/icone/spunta.png"
                                                         alt="Rischio vento" title="Rischio vento" />
                                                                                            </div>
                                        </div>
                                        <div class="al-container-padded left al-width-33-pct">
                                            <div class="al-table-cell al-background-white">
                                                                                            </div>
                                        </div>
                                        <div class="al-container-padded right al-width-33-pct">
                                            <div class="al-table-cell al-background-white">
                                                                                            </div>
                                        </div>
                                    </div>

                                    <!-- Rischi meteo zona E -->
                                    <div class="al-container al-background-lightgray">
                                        <div class="al-container-padded left al-width-33-pct">
                                            <div class="al-table-cell al-background-white">
                                                                                                    <img src="img/icone/spunta.png"
                                                         alt="Rischio vento" title="Rischio vento" />
                                                                                            </div>
                                        </div>
                                        <div class="al-container-padded left al-width-33-pct">
                                            <div class="al-table-cell al-background-white">
                                                                                            </div>
                                        </div>
                                        <div class="al-container-padded right al-width-33-pct">
                                            <div class="al-table-cell al-background-white">
                                                                                            </div>
                                        </div>
                                    </div>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </section>

        
        <section style="margin-top: 15px">
            <div class="row" style="margin-top: 15px">
                <div class="large-12 medium-12 columns">
                    <div class="row" data-equalizer>
                        <div class="large-4 medium-4 columns" data-equalizer-watch>
                            <div class="al-container al-legenda-panel al-position-relative" style="height: 100%">
    <h1 class="al-color-verydarkgray" style="margin-top: 0px">LEGENDA LIVELLI ALLERTA</h1>
    <div class="al-container" style="margin-bottom: 60px">
        <div class="al-container">
    <p><b>Livelli allerta idrogeologica, idraulica e nivologica</b></p>
</div>
<div class="al-container al-accordion-legenda" style="margin-top: 5px">
    <dl class="accordion" data-accordion="">
        <dt></dt>
        <dd id="al-accordion-legenda-elem-temporali" class="accordion-navigation ">
            <a href="#al-panel-temporali">
                <div class="al-accordion-legenda-elem-header">
                    <h2>TEMPORALI</h2>
                </div>
            </a>
            <div id="al-panel-temporali" class="content  al-accordion-legenda-elem-body">
                <div class="al-container">
                    <div class="al-container al-livello-allerta" style="margin-top: 5px">
                        <div class="al-container left al-width-25-pct">
                            <div class="al-table-cell al-background-allerta-green">
                                <p>VERDE</p>
                            </div>
                        </div>
                        <div class="al-container al-parent-centered al-width-75-pct">
                            <div class="al-child-centered" style="height: 50px">
                                <p class="al-descrizione-allerta">Assenza o bassa probabilità a livello locale di fenomeni significativi prevedibili.</p>
                            </div>
                        </div>
                    </div>
                    <div class="al-container al-livello-allerta">
                        <div class="al-container left al-width-25-pct">
                            <div class="al-table-cell al-background-allerta-yellow">
                                <p>GIALLA</p>
                            </div>
                        </div>
                        <div class="al-container al-parent-centered al-width-75-pct">
                            <div class="al-child-centered" style="height: 50px">
                                <p class="al-descrizione-allerta">Occasionale pericolo: fenomeni puntuali anche intensi e repentini.</p>
                            </div>
                        </div>
                    </div>
                    <div class="al-container al-livello-allerta">
                        <div class="al-container left al-width-25-pct">
                            <div class="al-table-cell al-background-allerta-orange">
                                <p>ARANCIONE</p>
                            </div>
                        </div>
                        <div class="al-container al-parent-centered al-width-75-pct">
                            <div class="al-child-centered" style="height: 50px">
                                <p class="al-descrizione-allerta">Pericolo: massima gravità per fenomeni puntuali anche molto intensi, repentini e persistenti.</p>
                            </div>
                        </div>
                    </div>
                    <div class="al-container al-livello-allerta">
                        <div class="al-container left al-width-25-pct">
                            <div class="al-table-cell al-background-allerta-red">
                                <p>ROSSA</p>
                            </div>
                        </div>
                        <div class="al-container al-parent-centered al-width-75-pct">
                            <div class="al-child-centered" style="height: 50px">
                                <p class="al-descrizione-allerta">Codice non previsto per temporali (solo fenomeni estesi).</p>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </dd>
        <dt></dt>
        <dd id="al-accordion-legenda-elem-piogge-diffuse" class="accordion-navigation active">
            <a href="#al-panel-piogge-diffuse">
                <div class="al-accordion-legenda-elem-header">
                    <h2>PIOGGE DIFFUSE</h2>
                </div>
            </a>
            <div id="al-panel-piogge-diffuse" class="content active al-accordion-legenda-elem-body">
                <div class="al-container">
                    <div class="al-container al-livello-allerta" style="margin-top: 5px">
                        <div class="al-container left al-width-25-pct">
                            <div class="al-table-cell al-background-allerta-green">
                                <p>VERDE</p>
                            </div>
                        </div>
                        <div class="al-container al-parent-centered al-width-75-pct">
                            <div class="al-child-centered" style="height: 50px">
                                <p class="al-descrizione-allerta">Assenza o bassa probabilità a livello locale di fenomeni significativi prevedibili.</p>
                            </div>
                        </div>
                    </div>
                    <div class="al-container al-livello-allerta">
                        <div class="al-container left al-width-25-pct">
                            <div class="al-table-cell al-background-allerta-yellow">
                                <p>GIALLA</p>
                            </div>
                        </div>
                        <div class="al-container al-parent-centered al-width-75-pct">
                            <div class="al-child-centered" style="height: 50px">
                                <p class="al-descrizione-allerta">Occasionale pericolo: fenomeni ed effetti locali.</p>
                            </div>
                        </div>
                    </div>
                    <div class="al-container al-livello-allerta">
                        <div class="al-container left al-width-25-pct">
                            <div class="al-table-cell al-background-allerta-orange">
                                <p>ARANCIONE</p>
                            </div>
                        </div>
                        <div class="al-container al-parent-centered al-width-75-pct">
                            <div class="al-child-centered" style="height: 50px">
                                <p class="al-descrizione-allerta">Pericolo: fenomeni ed effetti diffusi.</p>
                            </div>
                        </div>
                    </div>
                    <div class="al-container al-livello-allerta">
                        <div class="al-container left al-width-25-pct">
                            <div class="al-table-cell al-background-allerta-red">
                                <p>ROSSA</p>
                            </div>
                        </div>
                        <div class="al-container al-parent-centered al-width-75-pct">
                            <div class="al-child-centered" style="height: 50px">
                                <p class="al-descrizione-allerta">Grave pericolo: fenomeni ed effetti ingenti ed estesi.</p>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </dd>
        <dt></dt>
        <dd id="al-accordion-legenda-elem-neve" class="accordion-navigation ">
            <a href="#al-panel-neve">
                <div class="al-accordion-legenda-elem-header">
                    <h2>NEVE</h2>
                </div>
            </a>
            <div id="al-panel-neve" class="content  al-accordion-legenda-elem-body">
                <div class="al-container">
                    <div class="al-container al-livello-allerta" style="margin-top: 5px">
                        <div class="al-container left al-width-25-pct">
                            <div class="al-table-cell al-background-allerta-green">
                                <p>VERDE</p>
                            </div>
                        </div>
                        <div class="al-container al-parent-centered al-width-75-pct">
                            <div class="al-child-centered" style="height: 50px">
                                <p class="al-descrizione-allerta">Assenza o bassa probabilità a livello locale di fenomeni significativi prevedibili.</p>
                            </div>
                        </div>
                    </div>
                    <div class="al-container al-livello-allerta">
                        <div class="al-container left al-width-25-pct">
                            <div class="al-table-cell al-background-allerta-yellow">
                                <p>GIALLA</p>
                            </div>
                        </div>
                        <div class="al-container al-parent-centered al-width-75-pct">
                            <div class="al-child-centered" style="height: 50px">
                                <p class="al-descrizione-allerta">Disagio locale e problemi temporanei a viabilità.</p>
                            </div>
                        </div>
                    </div>
                    <div class="al-container al-livello-allerta">
                        <div class="al-container left al-width-25-pct">
                            <div class="al-table-cell al-background-allerta-orange">
                                <p>ARANCIONE</p>
                            </div>
                        </div>
                        <div class="al-container al-parent-centered al-width-75-pct">
                            <div class="al-child-centered" style="height: 50px">
                                <p class="al-descrizione-allerta">Disagio diffuso e problemi prolungati a viabilità.</p>
                            </div>
                        </div>
                    </div>
                    <div class="al-container al-livello-allerta">
                        <div class="al-container left al-width-25-pct">
                            <div class="al-table-cell al-background-allerta-red">
                                <p>ROSSA</p>
                            </div>
                        </div>
                        <div class="al-container al-parent-centered al-width-75-pct">
                            <div class="al-child-centered" style="height: 50px">
                                <p class="al-descrizione-allerta">Pericolo e problemi prolungati ed estesi a viabilità.</p>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </dd>
    </dl>
</div>    </div>
        <div class="al-container al-position-absolute al-position-bottom al-position-right" style="margin-top: 10px">
        <div class="al-container">
            <a class="small button al-button-lightgray"
               href="livelli_allerta_rischi.php">Vai alla GUIDA</a>
        </div>
    </div>
</div>                        </div>
                        <div class="large-4 medium-4 columns" data-equalizer-watch>
                            <div class="panel al-container al-position-relative al-messaggi-panel" style="height: 100%">
                                <div class="al-container al-parent-centered" style="height: 36px">
                                    <div class="al-logo-messaggio-protezione-civile left" style="height: 36px; width: 36px">
                                        <img src="img/loghi/logo_protezione_civile_small.png"
                                             alt="Protezione Civile Regione Liguria" title="Protezione Civile Regione Liguria" />
                                    </div>
                                    <h2 class="al-color-verydarkgray al-child-centered">MESSAGGIO DI ALLERTA della Regione Liguria</h2>
                                </div>
                                <div class="al-container" style="margin-top: 10px">
                                    <img src="img/varie/sala_controllo.png" style="width: 100%"
                                        alt="Messaggio di allerta della Regione Liguria" title="Messaggio di allerta della Regione Liguria" />
                                </div>
                                <div class="al-container" style="margin-top: 10px; margin-bottom: 40px">
                                                                        
                                    <p>
                                        Nessuna allerta                                    </p>
                                </div>
                                                            </div>
                        </div>
                        <div class="large-4 medium-4 columns" data-equalizer-watch>
                            <div class="panel al-container al-position-relative al-messaggi-panel" style="height: 100%">
                                <div class="al-container al-parent-centered" style="height: 36px">
                                    <div class="al-logo-messaggio-arpal left" style="height: 36px; width: 36px">
                                        <img src="img/loghi/logo_arpal_small.png"
                                             alt="ARPAL" title="ARPAL" />
                                    </div>
                                    <h2 class="al-color-verydarkgray al-child-centered">PREVISIONI METEO di ARPAL</h2>
                                </div>
                                <div class="al-container" style="margin-top: 10px">
                                    <img src="img/varie/sala_controllo.png" style="width: 100%"
                                        alt="Messaggio meteo di ARPAL" title="Messaggio meteo di ARPAL" />
                                </div>
                                <div class="al-container" style="margin-top: 10px; margin-bottom: 40px">
                                                                            <p style="margin-bottom: 10px">
                                            <span>Data emissione: </span>
                                            <span class="al-text-italic">
                                                26 novembre 2016 ore 08:50                                            </span>
                                        </p>
                                                                        
                                    <p>
                                        Consulta il Bollettino di Vigilanza/Avviso Meteorologico regionale per i dettagli previsionali.                                    </p>
                                </div>
                                                                    <div class="al-container right al-position-absolute al-position-bottom al-position-right hide-for-small">
                                        
<div class="al-container">
    <a class="small button al-button-lightgray" target="_blank" href="docs/vigilanza_22217.pdf">
        <span class="al-button-caption">
            Scarica il PDF  
        </span>
        <span class="al-button-filesize">
             (0.09 MB)        </span>
        <img src="img/icone/pdf_icon_small.png"
             alt="Scarica il file in formato PDF"
             title="Scarica il file in formato PDF" />
    </a>
</div>                                    </div>
                                    <div class="al-container right al-position-right show-for-small">
                                        
<div class="al-container">
    <a class="small button al-button-lightgray" target="_blank" href="docs/vigilanza_22217.pdf">
        <span class="al-button-caption">
            Scarica il PDF  
        </span>
        <span class="al-button-filesize">
             (0.09 MB)        </span>
        <img src="img/icone/pdf_icon_small.png"
             alt="Scarica il file in formato PDF"
             title="Scarica il file in formato PDF" />
    </a>
</div>                                    </div>
                                                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </section>

        <section class="al-background-verydarkgray al-position-relative" style="padding-top: 20px; padding-bottom: 20px; margin-top: 15px">
    <div id="al-panel-monitoraggio" class="al-position-absolute al-offset-down"></div>
    <div class="row">
        <div class="large-12 medium-12 small-12 columns">
            <h1 class="al-title al-color-gray" style="margin-top: 5px">Situazione in atto</h1>
        </div>
    </div>
    <div class="row" style="margin-top: 20px" data-equalizer>
        <div class="large-4 medium-4 columns" data-equalizer-watch>
            <div class="panel al-container al-position-relative al-messaggi-protciv-monitoraggio-panel al-background-verydarkgray" style="height: 100%">
                <div class="al-container al-parent-centered" style="height: 36px">
                    <div class="al-logo-messaggio-protezione-civile left" style="height: 36px; width: 36px">
                        <img src="img/loghi/logo_protezione_civile_small.png"
                             alt="Protezione Civile Regione Liguria" title="Protezione Civile Regione Liguria" />
                    </div>
                    <h2 class="al-child-centered">COMUNICAZIONI PROT. CIVILE della Regione Liguria</h2>
                </div>
                <div class="al-container" style="margin-top: 10px; margin-bottom: 40px">
                                        
                    <p>
                        Sala operativa aperta.<br />
<br />
		Contatti: tel: 010.5485990 - 010.5485991<br />
		Attività di monitoraggio in corso.                    </p>
                </div>
            </div>
        </div>
        <div class="large-4 medium-4 columns" data-equalizer-watch>
            <div class="panel al-container al-position-relative al-messaggi-monitoraggio-panel" style="height: 100%">
                <div class="al-container al-parent-centered" style="height: 36px">
                    <div class="al-logo-messaggio-arpal left" style="height: 36px; width: 36px">
                        <img src="img/loghi/logo_arpal_small.png" alt="ARPAL" title="ARPAL" />
                    </div>
                    <h2 class="al-color-verydarkgray al-child-centered">MONITORAGGIO METEO IDRO di ARPAL</h2>
                </div>
                <div class="al-container" style="margin-top: 10px; margin-bottom: 40px">
                                            <p style="margin-bottom: 10px">
                            <span>Data emissione: </span>
                            <span class="al-text-italic">
                                25 novembre 2016 ore 10:56                            </span>
                        </p>
                                        
                    <p>
                        Nelle ultime ore è stata registrata una generale attenuazione delle intensità di precipitazione, pur con locali fenomeni moderati accompagnati da rinforzi di vento.<br />
Attualmente sono osservate precipitazioni deboli e sparse, in particolare sul savonese.<br />
Ciò premesso, si sta...                    </p>
                </div>
                                    <div class="al-container right al-position-absolute al-position-bottom al-position-right hide-for-small">
                        <div class="al-container">
                            <a class="small button al-button-lightgray"
                               href="messaggi_monitoraggio_arpal.php">LEGGI TUTTO</a>
                        </div>
                    </div>
                    <div class="al-container right al-position-right show-for-small">
                        <div class="al-container">
                            <a class="small button al-button-lightgray"
                               href="messaggi_monitoraggio_arpal.php">LEGGI TUTTO</a>
                        </div>
                    </div>
                            </div>
        </div>
        <div class="large-4 medium-4 columns" data-equalizer-watch>
            <div class="panel al-container al-position-relative al-messaggi-monitoraggio-panel" style="height: 100%">
                <div class="al-container al-parent-centered" style="height: 36px">
                    <div class="al-logo-messaggio-arpal left" style="height: 36px; width: 36px">
                        <img src="img/loghi/logo_arpal_small.png" alt="ARPAL" title="ARPAL" />
                    </div>
                    <h2 class="al-color-verydarkgray al-child-centered">DATI IN TEMPO REALE</h2>
                </div>
                <div class="al-container" style="margin-top: 10px; margin-bottom: 40px">
                    <img src="img/mappe/mappe_prec.png"
                         alt="Esempio di mappa precipitazioni in tempo reale"
                         title="Esempio di mappa precipitazioni in tempo reale" />
                </div>
                <div class="al-container right al-position-absolute al-position-bottom al-position-right hide-for-small">
                    <div class="al-container">
                        <a class="small button al-button-lightgray"
                           href="dati_tempo_reale.php">VEDI TUTTI I DATI</a>
                    </div>
                </div>
                <div class="al-container right al-position-right show-for-small">
                    <div class="al-container">
                        <a class="small button al-button-lightgray"
                           href="dati_tempo_reale.php">VEDI TUTTI I DATI</a>
                    </div>
                </div>
            </div>
        </div>
    </div>
</section>
        <div class="row">
            <div class="large-12 medium-12 columns">
                <div class="row">
                    <div class="large-12 columns">
                        <div class="al-title al-color-verydarkgray" style="margin-top: 25px">
                            Dettaglio previsionale per zona
                        </div>
                        <div class="al-accordion-zone-panel">
                            <dl class="accordion" data-accordion="">
                                
<dt></dt>
<dd id="al-accordion-zone-elem-A" class="accordion-navigation al-position-relative">
    
    <div id="al-zona-A" class="al-position-absolute al-offset-down"></div>

            <div class="al-container al-accordion-zone-header al-background-allerta-lightgray">
            <div class="al-container left hide-for-small">
                <div class="al-container al-parent-centered al-accordion-zone-header-image left">
                    <div class="al-container al-child-centered">
                        <img src="img/mappe/AREA_A_V.png" alt="Zona A" title="Zona A" />
                    </div>
                </div>
            </div>
            <div class="al-container left hide-for-small">
                <div class="al-container al-parent-centered al-accordion-zone-header-title-zona left">
                    <div class="al-container al-child-centered al-text-horz-center">
                        <h3 class="al-display-inline al-color-white">zona </h3>
                    </div>
                </div>
            </div>
            <div class="al-container left">
                <div class="al-container al-parent-centered al-accordion-zone-header-title-cod-zona left">
                    <div class="al-container al-child-centered al-text-horz-center">
                        <h4 class="al-display-inline al-color-white">A</h4>
                    </div>
                </div>
            </div>
            <div class="al-container al-parent-centered al-accordion-zone-header-message left">
                <div class="al-container al-child-centered">
                    <h6 class="al-display-inline al-accordion-zone-header-message-font-size">Nessuna allerta</h6>
                </div>
            </div>
        </div>
        <div id="panelA" class="content">
        <div class="row">
            <div class="large-8 medium-8 small-12 columns">
                
                <!-- Dettaglio rischio meteo zona -->
                                <div class="al-container al-width-100-pct al-background-darkgray">
                    <div class="row">
                        <div class="large-12 medium-12 small-12 columns al-parent-centered al-accordion-zone-subheader-message left" style="height: 60px">
                            <div class="al-container al-child-centered" style="padding-left: 15px; padding-right: 15px">
                                <h1 class="al-color-white">ALTRI RISCHI METEO<!-- ZONA A--></h1>
                            </div>
                        </div>
                    </div>
                </div>
                <div class="row">
                    <div class="large-6 medium-6 small-12 columns">

                        <div class="al-container al-standard-panel">

                            <div class="al-container">
                                <div class="al-container" style="margin-bottom: 5px">
                                                                        <div class="al-container-padded-right left al-width-33-pct">
                                        <p style="text-align: center">Vento</p>
                                    </div>
                                                                    </div>
                                <div class="al-container">
                                                                        <div class="al-container-padded-right left al-width-33-pct">
                                        <div class="al-table-cell-icon">
                                            <img class="al-background-white" 
                                                 src="img/icone/VENTO_FORTE_N_BIANCO.png"
                                                 style="width: 48px; height: 48px"
                                                 alt="Vento forte n bianco"
                                                 title="Vento forte n bianco" />
                                        </div>
                                    </div>
                                                                    </div>

                                
                            </div>

                        </div>

                    </div>

                    <div class="large-6 medium-6 columns hide-for-small">



                    </div>
                </div>
                            </div>
            <div class="large-4 medium-4 hide-for-small columns">
                <div class="al-container al-legenda-detail-panel">
    <div class="al-container al-parent-centered al-width-100-pct">
        <div class="al-container al-child-centered al-width-50-pct">
            <p class="al-color-verydarkgray al-title">Legenda</p>
        </div>
        <div class="al-container al-child-centered al-width-50-pct">
            <a href="livelli_allerta_rischi.php"><h2 class="al-color-verydarkgray right">VAI ALLA GUIDA &gt;&gt;</h2></a>
        </div>
    </div>
    <div class="al-container">
    <p><b>Livelli allerta idrogeologica, idraulica e nivologica</b></p>
</div>
<div class="al-container al-accordion-legenda" style="margin-top: 5px">
    <dl class="accordion" data-accordion="">
        <dt></dt>
        <dd id="al-accordion-legenda-elem-temporali-A" class="accordion-navigation ">
            <a href="#al-panel-temporali-A">
                <div class="al-accordion-legenda-elem-header">
                    <h2>TEMPORALI</h2>
                </div>
            </a>
            <div id="al-panel-temporali-A" class="content  al-accordion-legenda-elem-body">
                <div class="al-container">
                    <div class="al-container al-livello-allerta" style="margin-top: 5px">
                        <div class="al-container left al-width-25-pct">
                            <div class="al-table-cell al-background-allerta-green">
                                <p>VERDE</p>
                            </div>
                        </div>
                        <div class="al-container al-parent-centered al-width-75-pct">
                            <div class="al-child-centered" style="height: 50px">
                                <p class="al-descrizione-allerta">Assenza o bassa probabilità a livello locale di fenomeni significativi prevedibili.</p>
                            </div>
                        </div>
                    </div>
                    <div class="al-container al-livello-allerta">
                        <div class="al-container left al-width-25-pct">
                            <div class="al-table-cell al-background-allerta-yellow">
                                <p>GIALLA</p>
                            </div>
                        </div>
                        <div class="al-container al-parent-centered al-width-75-pct">
                            <div class="al-child-centered" style="height: 50px">
                                <p class="al-descrizione-allerta">Occasionale pericolo: fenomeni puntuali anche intensi e repentini.</p>
                            </div>
                        </div>
                    </div>
                    <div class="al-container al-livello-allerta">
                        <div class="al-container left al-width-25-pct">
                            <div class="al-table-cell al-background-allerta-orange">
                                <p>ARANCIONE</p>
                            </div>
                        </div>
                        <div class="al-container al-parent-centered al-width-75-pct">
                            <div class="al-child-centered" style="height: 50px">
                                <p class="al-descrizione-allerta">Pericolo: massima gravità per fenomeni puntuali anche molto intensi, repentini e persistenti.</p>
                            </div>
                        </div>
                    </div>
                    <div class="al-container al-livello-allerta">
                        <div class="al-container left al-width-25-pct">
                            <div class="al-table-cell al-background-allerta-red">
                                <p>ROSSA</p>
                            </div>
                        </div>
                        <div class="al-container al-parent-centered al-width-75-pct">
                            <div class="al-child-centered" style="height: 50px">
                                <p class="al-descrizione-allerta">Codice non previsto per temporali (solo fenomeni estesi).</p>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </dd>
        <dt></dt>
        <dd id="al-accordion-legenda-elem-piogge-diffuse-A" class="accordion-navigation active">
            <a href="#al-panel-piogge-diffuse-A">
                <div class="al-accordion-legenda-elem-header">
                    <h2>PIOGGE DIFFUSE</h2>
                </div>
            </a>
            <div id="al-panel-piogge-diffuse-A" class="content active al-accordion-legenda-elem-body">
                <div class="al-container">
                    <div class="al-container al-livello-allerta" style="margin-top: 5px">
                        <div class="al-container left al-width-25-pct">
                            <div class="al-table-cell al-background-allerta-green">
                                <p>VERDE</p>
                            </div>
                        </div>
                        <div class="al-container al-parent-centered al-width-75-pct">
                            <div class="al-child-centered" style="height: 50px">
                                <p class="al-descrizione-allerta">Assenza o bassa probabilità a livello locale di fenomeni significativi prevedibili.</p>
                            </div>
                        </div>
                    </div>
                    <div class="al-container al-livello-allerta">
                        <div class="al-container left al-width-25-pct">
                            <div class="al-table-cell al-background-allerta-yellow">
                                <p>GIALLA</p>
                            </div>
                        </div>
                        <div class="al-container al-parent-centered al-width-75-pct">
                            <div class="al-child-centered" style="height: 50px">
                                <p class="al-descrizione-allerta">Occasionale pericolo: fenomeni ed effetti locali.</p>
                            </div>
                        </div>
                    </div>
                    <div class="al-container al-livello-allerta">
                        <div class="al-container left al-width-25-pct">
                            <div class="al-table-cell al-background-allerta-orange">
                                <p>ARANCIONE</p>
                            </div>
                        </div>
                        <div class="al-container al-parent-centered al-width-75-pct">
                            <div class="al-child-centered" style="height: 50px">
                                <p class="al-descrizione-allerta">Pericolo: fenomeni ed effetti diffusi.</p>
                            </div>
                        </div>
                    </div>
                    <div class="al-container al-livello-allerta">
                        <div class="al-container left al-width-25-pct">
                            <div class="al-table-cell al-background-allerta-red">
                                <p>ROSSA</p>
                            </div>
                        </div>
                        <div class="al-container al-parent-centered al-width-75-pct">
                            <div class="al-child-centered" style="height: 50px">
                                <p class="al-descrizione-allerta">Grave pericolo: fenomeni ed effetti ingenti ed estesi.</p>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </dd>
        <dt></dt>
        <dd id="al-accordion-legenda-elem-neve-A" class="accordion-navigation ">
            <a href="#al-panel-neve-A">
                <div class="al-accordion-legenda-elem-header">
                    <h2>NEVE</h2>
                </div>
            </a>
            <div id="al-panel-neve-A" class="content  al-accordion-legenda-elem-body">
                <div class="al-container">
                    <div class="al-container al-livello-allerta" style="margin-top: 5px">
                        <div class="al-container left al-width-25-pct">
                            <div class="al-table-cell al-background-allerta-green">
                                <p>VERDE</p>
                            </div>
                        </div>
                        <div class="al-container al-parent-centered al-width-75-pct">
                            <div class="al-child-centered" style="height: 50px">
                                <p class="al-descrizione-allerta">Assenza o bassa probabilità a livello locale di fenomeni significativi prevedibili.</p>
                            </div>
                        </div>
                    </div>
                    <div class="al-container al-livello-allerta">
                        <div class="al-container left al-width-25-pct">
                            <div class="al-table-cell al-background-allerta-yellow">
                                <p>GIALLA</p>
                            </div>
                        </div>
                        <div class="al-container al-parent-centered al-width-75-pct">
                            <div class="al-child-centered" style="height: 50px">
                                <p class="al-descrizione-allerta">Disagio locale e problemi temporanei a viabilità.</p>
                            </div>
                        </div>
                    </div>
                    <div class="al-container al-livello-allerta">
                        <div class="al-container left al-width-25-pct">
                            <div class="al-table-cell al-background-allerta-orange">
                                <p>ARANCIONE</p>
                            </div>
                        </div>
                        <div class="al-container al-parent-centered al-width-75-pct">
                            <div class="al-child-centered" style="height: 50px">
                                <p class="al-descrizione-allerta">Disagio diffuso e problemi prolungati a viabilità.</p>
                            </div>
                        </div>
                    </div>
                    <div class="al-container al-livello-allerta">
                        <div class="al-container left al-width-25-pct">
                            <div class="al-table-cell al-background-allerta-red">
                                <p>ROSSA</p>
                            </div>
                        </div>
                        <div class="al-container al-parent-centered al-width-75-pct">
                            <div class="al-child-centered" style="height: 50px">
                                <p class="al-descrizione-allerta">Pericolo e problemi prolungati ed estesi a viabilità.</p>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </dd>
    </dl>
</div>    <div style="margin-top: 15px">
    <div class="al-container">
        <div class="al-container">
            <p class="al-text-bold">Simboli meteo</p>
        </div>
    </div>
</div>
<div class="al-container" style="margin-top: 5px">
    <div class="al-container-padded-right left al-width-33-pct al-parent-centered" style="text-align: center">
        <div class="al-child-centered" style="height: 31px; width: 48px; text-align: center">
            <img src="img/icone/nuvola_transparent.png" style="width: 37px" alt="Fenomeni significativi" title="Fenomeni significativi" />
        </div>
    </div>
    <div class="al-container-padded-right left al-width-33-pct al-parent-centered" style="text-align: center">
        <div class="al-child-centered" style="height: 31px; width: 48px; text-align: center">
            <img src="img/icone/nuvola_lightgray.png" style="width: 37px" alt="Fenomeni intensi" title="Fenomeni intensi" />
        </div>
    </div>
    <div class="al-container-padded-left right al-width-33-pct al-parent-centered" style="text-align: center">
        <div class="al-child-centered" style="height: 31px; width: 48px">
            <img src="img/icone/nuvola_darkgray.png" style="width: 37px" alt="Fenomeni molto intensi" title="Fenomeni molto intensi" />
        </div>
    </div>
</div>
<div class="al-container" style="margin-bottom: 10px">
    <div class="al-container-padded-right left al-width-33-pct">
        <p style="line-height: 0.75rem; font-size: 10px; text-align: center">Fenomeni significativi</p>
    </div>
    <div class="al-container-padded-right left al-width-33-pct">
        <p style="line-height: 0.75rem; font-size: 10px; text-align: center">Fenomeni intensi</p>
    </div>
    <div class="al-container-padded-left right al-width-33-pct">
        <p style="line-height: 0.75rem; font-size: 10px; text-align: center">Fenomeni molto intensi</p>
    </div>
</div>
<div class="al-container" style="margin-top: 15px">
    <div class="al-container right">
        
<div class="al-container">
    <a class="small button al-button-lightgray" target="_blank" href="docs/elenco_soglie_meteoidrologiche.pdf">
        <span class="al-button-caption">
            Scarica il PDF  
        </span>
        <span class="al-button-filesize">
             (0.47 MB)        </span>
        <img src="img/icone/pdf_icon_small.png"
             alt="Scarica il file in formato PDF"
             title="Scarica il file in formato PDF" />
    </a>
</div>    </div>
</div>    <div style="margin-top: 15px">
    <p><b>Divisione del territorio</b></p>
</div>
<div class="al-container" style="margin-top: 5px; height: 50px">
    <div class="al-container-padded-right left al-width-40-pct al-parent-centered" style="height: 100%">
        <div class="al-child-centered" style="height: 46px; width: 90px; text-align: center">
            <img src="img/icone/divisione_territorio.png" style="width: 90px" alt="Zone di allerta" title="Zone di allerta" />
        </div>
    </div>
    <div class="al-container-padded-left al-width-60-pct al-parent-centered" style="height: 100%">
        <div class="al-container al-child-centered right">
            <div class="al-container">
                <a class="small button al-button-lightgray"
                   href="divisione_territorio.php">Vai alla GUIDA</a>
            </div>
        </div>
    </div>
</div></div>            </div>
        </div>
    </div>
</dd>

<dt></dt>
<dd id="al-accordion-zone-elem-B" class="accordion-navigation al-position-relative">
    
    <div id="al-zona-B" class="al-position-absolute al-offset-down"></div>

            <div class="al-container al-accordion-zone-header al-background-allerta-lightgray">
            <div class="al-container left hide-for-small">
                <div class="al-container al-parent-centered al-accordion-zone-header-image left">
                    <div class="al-container al-child-centered">
                        <img src="img/mappe/AREA_B_V.png" alt="Zona B" title="Zona B" />
                    </div>
                </div>
            </div>
            <div class="al-container left hide-for-small">
                <div class="al-container al-parent-centered al-accordion-zone-header-title-zona left">
                    <div class="al-container al-child-centered al-text-horz-center">
                        <h3 class="al-display-inline al-color-white">zona </h3>
                    </div>
                </div>
            </div>
            <div class="al-container left">
                <div class="al-container al-parent-centered al-accordion-zone-header-title-cod-zona left">
                    <div class="al-container al-child-centered al-text-horz-center">
                        <h4 class="al-display-inline al-color-white">B</h4>
                    </div>
                </div>
            </div>
            <div class="al-container al-parent-centered al-accordion-zone-header-message left">
                <div class="al-container al-child-centered">
                    <h6 class="al-display-inline al-accordion-zone-header-message-font-size">Nessuna allerta</h6>
                </div>
            </div>
        </div>
        <div id="panelB" class="content">
        <div class="row">
            <div class="large-8 medium-8 small-12 columns">
                
                <!-- Dettaglio rischio meteo zona -->
                                <div class="al-container al-width-100-pct al-background-darkgray">
                    <div class="row">
                        <div class="large-12 medium-12 small-12 columns al-parent-centered al-accordion-zone-subheader-message left" style="height: 60px">
                            <div class="al-container al-child-centered" style="padding-left: 15px; padding-right: 15px">
                                <h1 class="al-color-white">ALTRI RISCHI METEO<!-- ZONA B--></h1>
                            </div>
                        </div>
                    </div>
                </div>
                <div class="row">
                    <div class="large-6 medium-6 small-12 columns">

                        <div class="al-container al-standard-panel">

                            <div class="al-container">
                                <div class="al-container" style="margin-bottom: 5px">
                                                                        <div class="al-container-padded-right left al-width-33-pct">
                                        <p style="text-align: center">Vento</p>
                                    </div>
                                                                    </div>
                                <div class="al-container">
                                                                        <div class="al-container-padded-right left al-width-33-pct">
                                        <div class="al-table-cell-icon">
                                            <img class="al-background-white" 
                                                 src="img/icone/VENTO_FORTE_N_BIANCO.png"
                                                 style="width: 48px; height: 48px"
                                                 alt="Vento forte n bianco"
                                                 title="Vento forte n bianco" />
                                        </div>
                                    </div>
                                                                    </div>

                                
                            </div>

                        </div>

                    </div>

                    <div class="large-6 medium-6 columns hide-for-small">



                    </div>
                </div>
                            </div>
            <div class="large-4 medium-4 hide-for-small columns">
                <div class="al-container al-legenda-detail-panel">
    <div class="al-container al-parent-centered al-width-100-pct">
        <div class="al-container al-child-centered al-width-50-pct">
            <p class="al-color-verydarkgray al-title">Legenda</p>
        </div>
        <div class="al-container al-child-centered al-width-50-pct">
            <a href="livelli_allerta_rischi.php"><h2 class="al-color-verydarkgray right">VAI ALLA GUIDA &gt;&gt;</h2></a>
        </div>
    </div>
    <div class="al-container">
    <p><b>Livelli allerta idrogeologica, idraulica e nivologica</b></p>
</div>
<div class="al-container al-accordion-legenda" style="margin-top: 5px">
    <dl class="accordion" data-accordion="">
        <dt></dt>
        <dd id="al-accordion-legenda-elem-temporali-B" class="accordion-navigation ">
            <a href="#al-panel-temporali-B">
                <div class="al-accordion-legenda-elem-header">
                    <h2>TEMPORALI</h2>
                </div>
            </a>
            <div id="al-panel-temporali-B" class="content  al-accordion-legenda-elem-body">
                <div class="al-container">
                    <div class="al-container al-livello-allerta" style="margin-top: 5px">
                        <div class="al-container left al-width-25-pct">
                            <div class="al-table-cell al-background-allerta-green">
                                <p>VERDE</p>
                            </div>
                        </div>
                        <div class="al-container al-parent-centered al-width-75-pct">
                            <div class="al-child-centered" style="height: 50px">
                                <p class="al-descrizione-allerta">Assenza o bassa probabilità a livello locale di fenomeni significativi prevedibili.</p>
                            </div>
                        </div>
                    </div>
                    <div class="al-container al-livello-allerta">
                        <div class="al-container left al-width-25-pct">
                            <div class="al-table-cell al-background-allerta-yellow">
                                <p>GIALLA</p>
                            </div>
                        </div>
                        <div class="al-container al-parent-centered al-width-75-pct">
                            <div class="al-child-centered" style="height: 50px">
                                <p class="al-descrizione-allerta">Occasionale pericolo: fenomeni puntuali anche intensi e repentini.</p>
                            </div>
                        </div>
                    </div>
                    <div class="al-container al-livello-allerta">
                        <div class="al-container left al-width-25-pct">
                            <div class="al-table-cell al-background-allerta-orange">
                                <p>ARANCIONE</p>
                            </div>
                        </div>
                        <div class="al-container al-parent-centered al-width-75-pct">
                            <div class="al-child-centered" style="height: 50px">
                                <p class="al-descrizione-allerta">Pericolo: massima gravità per fenomeni puntuali anche molto intensi, repentini e persistenti.</p>
                            </div>
                        </div>
                    </div>
                    <div class="al-container al-livello-allerta">
                        <div class="al-container left al-width-25-pct">
                            <div class="al-table-cell al-background-allerta-red">
                                <p>ROSSA</p>
                            </div>
                        </div>
                        <div class="al-container al-parent-centered al-width-75-pct">
                            <div class="al-child-centered" style="height: 50px">
                                <p class="al-descrizione-allerta">Codice non previsto per temporali (solo fenomeni estesi).</p>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </dd>
        <dt></dt>
        <dd id="al-accordion-legenda-elem-piogge-diffuse-B" class="accordion-navigation active">
            <a href="#al-panel-piogge-diffuse-B">
                <div class="al-accordion-legenda-elem-header">
                    <h2>PIOGGE DIFFUSE</h2>
                </div>
            </a>
            <div id="al-panel-piogge-diffuse-B" class="content active al-accordion-legenda-elem-body">
                <div class="al-container">
                    <div class="al-container al-livello-allerta" style="margin-top: 5px">
                        <div class="al-container left al-width-25-pct">
                            <div class="al-table-cell al-background-allerta-green">
                                <p>VERDE</p>
                            </div>
                        </div>
                        <div class="al-container al-parent-centered al-width-75-pct">
                            <div class="al-child-centered" style="height: 50px">
                                <p class="al-descrizione-allerta">Assenza o bassa probabilità a livello locale di fenomeni significativi prevedibili.</p>
                            </div>
                        </div>
                    </div>
                    <div class="al-container al-livello-allerta">
                        <div class="al-container left al-width-25-pct">
                            <div class="al-table-cell al-background-allerta-yellow">
                                <p>GIALLA</p>
                            </div>
                        </div>
                        <div class="al-container al-parent-centered al-width-75-pct">
                            <div class="al-child-centered" style="height: 50px">
                                <p class="al-descrizione-allerta">Occasionale pericolo: fenomeni ed effetti locali.</p>
                            </div>
                        </div>
                    </div>
                    <div class="al-container al-livello-allerta">
                        <div class="al-container left al-width-25-pct">
                            <div class="al-table-cell al-background-allerta-orange">
                                <p>ARANCIONE</p>
                            </div>
                        </div>
                        <div class="al-container al-parent-centered al-width-75-pct">
                            <div class="al-child-centered" style="height: 50px">
                                <p class="al-descrizione-allerta">Pericolo: fenomeni ed effetti diffusi.</p>
                            </div>
                        </div>
                    </div>
                    <div class="al-container al-livello-allerta">
                        <div class="al-container left al-width-25-pct">
                            <div class="al-table-cell al-background-allerta-red">
                                <p>ROSSA</p>
                            </div>
                        </div>
                        <div class="al-container al-parent-centered al-width-75-pct">
                            <div class="al-child-centered" style="height: 50px">
                                <p class="al-descrizione-allerta">Grave pericolo: fenomeni ed effetti ingenti ed estesi.</p>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </dd>
        <dt></dt>
        <dd id="al-accordion-legenda-elem-neve-B" class="accordion-navigation ">
            <a href="#al-panel-neve-B">
                <div class="al-accordion-legenda-elem-header">
                    <h2>NEVE</h2>
                </div>
            </a>
            <div id="al-panel-neve-B" class="content  al-accordion-legenda-elem-body">
                <div class="al-container">
                    <div class="al-container al-livello-allerta" style="margin-top: 5px">
                        <div class="al-container left al-width-25-pct">
                            <div class="al-table-cell al-background-allerta-green">
                                <p>VERDE</p>
                            </div>
                        </div>
                        <div class="al-container al-parent-centered al-width-75-pct">
                            <div class="al-child-centered" style="height: 50px">
                                <p class="al-descrizione-allerta">Assenza o bassa probabilità a livello locale di fenomeni significativi prevedibili.</p>
                            </div>
                        </div>
                    </div>
                    <div class="al-container al-livello-allerta">
                        <div class="al-container left al-width-25-pct">
                            <div class="al-table-cell al-background-allerta-yellow">
                                <p>GIALLA</p>
                            </div>
                        </div>
                        <div class="al-container al-parent-centered al-width-75-pct">
                            <div class="al-child-centered" style="height: 50px">
                                <p class="al-descrizione-allerta">Disagio locale e problemi temporanei a viabilità.</p>
                            </div>
                        </div>
                    </div>
                    <div class="al-container al-livello-allerta">
                        <div class="al-container left al-width-25-pct">
                            <div class="al-table-cell al-background-allerta-orange">
                                <p>ARANCIONE</p>
                            </div>
                        </div>
                        <div class="al-container al-parent-centered al-width-75-pct">
                            <div class="al-child-centered" style="height: 50px">
                                <p class="al-descrizione-allerta">Disagio diffuso e problemi prolungati a viabilità.</p>
                            </div>
                        </div>
                    </div>
                    <div class="al-container al-livello-allerta">
                        <div class="al-container left al-width-25-pct">
                            <div class="al-table-cell al-background-allerta-red">
                                <p>ROSSA</p>
                            </div>
                        </div>
                        <div class="al-container al-parent-centered al-width-75-pct">
                            <div class="al-child-centered" style="height: 50px">
                                <p class="al-descrizione-allerta">Pericolo e problemi prolungati ed estesi a viabilità.</p>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </dd>
    </dl>
</div>    <div style="margin-top: 15px">
    <div class="al-container">
        <div class="al-container">
            <p class="al-text-bold">Simboli meteo</p>
        </div>
    </div>
</div>
<div class="al-container" style="margin-top: 5px">
    <div class="al-container-padded-right left al-width-33-pct al-parent-centered" style="text-align: center">
        <div class="al-child-centered" style="height: 31px; width: 48px; text-align: center">
            <img src="img/icone/nuvola_transparent.png" style="width: 37px" alt="Fenomeni significativi" title="Fenomeni significativi" />
        </div>
    </div>
    <div class="al-container-padded-right left al-width-33-pct al-parent-centered" style="text-align: center">
        <div class="al-child-centered" style="height: 31px; width: 48px; text-align: center">
            <img src="img/icone/nuvola_lightgray.png" style="width: 37px" alt="Fenomeni intensi" title="Fenomeni intensi" />
        </div>
    </div>
    <div class="al-container-padded-left right al-width-33-pct al-parent-centered" style="text-align: center">
        <div class="al-child-centered" style="height: 31px; width: 48px">
            <img src="img/icone/nuvola_darkgray.png" style="width: 37px" alt="Fenomeni molto intensi" title="Fenomeni molto intensi" />
        </div>
    </div>
</div>
<div class="al-container" style="margin-bottom: 10px">
    <div class="al-container-padded-right left al-width-33-pct">
        <p style="line-height: 0.75rem; font-size: 10px; text-align: center">Fenomeni significativi</p>
    </div>
    <div class="al-container-padded-right left al-width-33-pct">
        <p style="line-height: 0.75rem; font-size: 10px; text-align: center">Fenomeni intensi</p>
    </div>
    <div class="al-container-padded-left right al-width-33-pct">
        <p style="line-height: 0.75rem; font-size: 10px; text-align: center">Fenomeni molto intensi</p>
    </div>
</div>
<div class="al-container" style="margin-top: 15px">
    <div class="al-container right">
        
<div class="al-container">
    <a class="small button al-button-lightgray" target="_blank" href="docs/elenco_soglie_meteoidrologiche.pdf">
        <span class="al-button-caption">
            Scarica il PDF  
        </span>
        <span class="al-button-filesize">
             (0.47 MB)        </span>
        <img src="img/icone/pdf_icon_small.png"
             alt="Scarica il file in formato PDF"
             title="Scarica il file in formato PDF" />
    </a>
</div>    </div>
</div>    <div style="margin-top: 15px">
    <p><b>Divisione del territorio</b></p>
</div>
<div class="al-container" style="margin-top: 5px; height: 50px">
    <div class="al-container-padded-right left al-width-40-pct al-parent-centered" style="height: 100%">
        <div class="al-child-centered" style="height: 46px; width: 90px; text-align: center">
            <img src="img/icone/divisione_territorio.png" style="width: 90px" alt="Zone di allerta" title="Zone di allerta" />
        </div>
    </div>
    <div class="al-container-padded-left al-width-60-pct al-parent-centered" style="height: 100%">
        <div class="al-container al-child-centered right">
            <div class="al-container">
                <a class="small button al-button-lightgray"
                   href="divisione_territorio.php">Vai alla GUIDA</a>
            </div>
        </div>
    </div>
</div></div>            </div>
        </div>
    </div>
</dd>

<dt></dt>
<dd id="al-accordion-zone-elem-C" class="accordion-navigation al-position-relative">
    
    <div id="al-zona-C" class="al-position-absolute al-offset-down"></div>

            <div class="al-container al-accordion-zone-header al-background-allerta-lightgray">
            <div class="al-container left hide-for-small">
                <div class="al-container al-parent-centered al-accordion-zone-header-image left">
                    <div class="al-container al-child-centered">
                        <img src="img/mappe/AREA_C_V.png" alt="Zona C" title="Zona C" />
                    </div>
                </div>
            </div>
            <div class="al-container left hide-for-small">
                <div class="al-container al-parent-centered al-accordion-zone-header-title-zona left">
                    <div class="al-container al-child-centered al-text-horz-center">
                        <h3 class="al-display-inline al-color-white">zona </h3>
                    </div>
                </div>
            </div>
            <div class="al-container left">
                <div class="al-container al-parent-centered al-accordion-zone-header-title-cod-zona left">
                    <div class="al-container al-child-centered al-text-horz-center">
                        <h4 class="al-display-inline al-color-white">C</h4>
                    </div>
                </div>
            </div>
            <div class="al-container al-parent-centered al-accordion-zone-header-message left">
                <div class="al-container al-child-centered">
                    <h6 class="al-display-inline al-accordion-zone-header-message-font-size">Nessuna allerta</h6>
                </div>
            </div>
        </div>
        <div id="panelC" class="content">
        <div class="row">
            <div class="large-8 medium-8 small-12 columns">
                
                <!-- Dettaglio rischio meteo zona -->
                                <div class="al-container al-width-100-pct al-background-darkgray">
                    <div class="row">
                        <div class="large-12 medium-12 small-12 columns al-parent-centered al-accordion-zone-subheader-message left" style="height: 60px">
                            <div class="al-container al-child-centered" style="padding-left: 15px; padding-right: 15px">
                                <h1 class="al-color-white">ALTRI RISCHI METEO<!-- ZONA C--></h1>
                            </div>
                        </div>
                    </div>
                </div>
                <div class="row">
                    <div class="large-6 medium-6 small-12 columns">

                        <div class="al-container al-standard-panel">

                            <div class="al-container">
                                <div class="al-container" style="margin-bottom: 5px">
                                                                        <div class="al-container-padded-right left al-width-33-pct">
                                        <p style="text-align: center">Vento</p>
                                    </div>
                                                                    </div>
                                <div class="al-container">
                                                                        <div class="al-container-padded-right left al-width-33-pct">
                                        <div class="al-table-cell-icon">
                                            <img class="al-background-white" 
                                                 src="img/icone/VENTO_FORTE_N_BIANCO.png"
                                                 style="width: 48px; height: 48px"
                                                 alt="Vento forte n bianco"
                                                 title="Vento forte n bianco" />
                                        </div>
                                    </div>
                                                                    </div>

                                
                            </div>

                        </div>

                    </div>

                    <div class="large-6 medium-6 columns hide-for-small">



                    </div>
                </div>
                            </div>
            <div class="large-4 medium-4 hide-for-small columns">
                <div class="al-container al-legenda-detail-panel">
    <div class="al-container al-parent-centered al-width-100-pct">
        <div class="al-container al-child-centered al-width-50-pct">
            <p class="al-color-verydarkgray al-title">Legenda</p>
        </div>
        <div class="al-container al-child-centered al-width-50-pct">
            <a href="livelli_allerta_rischi.php"><h2 class="al-color-verydarkgray right">VAI ALLA GUIDA &gt;&gt;</h2></a>
        </div>
    </div>
    <div class="al-container">
    <p><b>Livelli allerta idrogeologica, idraulica e nivologica</b></p>
</div>
<div class="al-container al-accordion-legenda" style="margin-top: 5px">
    <dl class="accordion" data-accordion="">
        <dt></dt>
        <dd id="al-accordion-legenda-elem-temporali-C" class="accordion-navigation ">
            <a href="#al-panel-temporali-C">
                <div class="al-accordion-legenda-elem-header">
                    <h2>TEMPORALI</h2>
                </div>
            </a>
            <div id="al-panel-temporali-C" class="content  al-accordion-legenda-elem-body">
                <div class="al-container">
                    <div class="al-container al-livello-allerta" style="margin-top: 5px">
                        <div class="al-container left al-width-25-pct">
                            <div class="al-table-cell al-background-allerta-green">
                                <p>VERDE</p>
                            </div>
                        </div>
                        <div class="al-container al-parent-centered al-width-75-pct">
                            <div class="al-child-centered" style="height: 50px">
                                <p class="al-descrizione-allerta">Assenza o bassa probabilità a livello locale di fenomeni significativi prevedibili.</p>
                            </div>
                        </div>
                    </div>
                    <div class="al-container al-livello-allerta">
                        <div class="al-container left al-width-25-pct">
                            <div class="al-table-cell al-background-allerta-yellow">
                                <p>GIALLA</p>
                            </div>
                        </div>
                        <div class="al-container al-parent-centered al-width-75-pct">
                            <div class="al-child-centered" style="height: 50px">
                                <p class="al-descrizione-allerta">Occasionale pericolo: fenomeni puntuali anche intensi e repentini.</p>
                            </div>
                        </div>
                    </div>
                    <div class="al-container al-livello-allerta">
                        <div class="al-container left al-width-25-pct">
                            <div class="al-table-cell al-background-allerta-orange">
                                <p>ARANCIONE</p>
                            </div>
                        </div>
                        <div class="al-container al-parent-centered al-width-75-pct">
                            <div class="al-child-centered" style="height: 50px">
                                <p class="al-descrizione-allerta">Pericolo: massima gravità per fenomeni puntuali anche molto intensi, repentini e persistenti.</p>
                            </div>
                        </div>
                    </div>
                    <div class="al-container al-livello-allerta">
                        <div class="al-container left al-width-25-pct">
                            <div class="al-table-cell al-background-allerta-red">
                                <p>ROSSA</p>
                            </div>
                        </div>
                        <div class="al-container al-parent-centered al-width-75-pct">
                            <div class="al-child-centered" style="height: 50px">
                                <p class="al-descrizione-allerta">Codice non previsto per temporali (solo fenomeni estesi).</p>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </dd>
        <dt></dt>
        <dd id="al-accordion-legenda-elem-piogge-diffuse-C" class="accordion-navigation active">
            <a href="#al-panel-piogge-diffuse-C">
                <div class="al-accordion-legenda-elem-header">
                    <h2>PIOGGE DIFFUSE</h2>
                </div>
            </a>
            <div id="al-panel-piogge-diffuse-C" class="content active al-accordion-legenda-elem-body">
                <div class="al-container">
                    <div class="al-container al-livello-allerta" style="margin-top: 5px">
                        <div class="al-container left al-width-25-pct">
                            <div class="al-table-cell al-background-allerta-green">
                                <p>VERDE</p>
                            </div>
                        </div>
                        <div class="al-container al-parent-centered al-width-75-pct">
                            <div class="al-child-centered" style="height: 50px">
                                <p class="al-descrizione-allerta">Assenza o bassa probabilità a livello locale di fenomeni significativi prevedibili.</p>
                            </div>
                        </div>
                    </div>
                    <div class="al-container al-livello-allerta">
                        <div class="al-container left al-width-25-pct">
                            <div class="al-table-cell al-background-allerta-yellow">
                                <p>GIALLA</p>
                            </div>
                        </div>
                        <div class="al-container al-parent-centered al-width-75-pct">
                            <div class="al-child-centered" style="height: 50px">
                                <p class="al-descrizione-allerta">Occasionale pericolo: fenomeni ed effetti locali.</p>
                            </div>
                        </div>
                    </div>
                    <div class="al-container al-livello-allerta">
                        <div class="al-container left al-width-25-pct">
                            <div class="al-table-cell al-background-allerta-orange">
                                <p>ARANCIONE</p>
                            </div>
                        </div>
                        <div class="al-container al-parent-centered al-width-75-pct">
                            <div class="al-child-centered" style="height: 50px">
                                <p class="al-descrizione-allerta">Pericolo: fenomeni ed effetti diffusi.</p>
                            </div>
                        </div>
                    </div>
                    <div class="al-container al-livello-allerta">
                        <div class="al-container left al-width-25-pct">
                            <div class="al-table-cell al-background-allerta-red">
                                <p>ROSSA</p>
                            </div>
                        </div>
                        <div class="al-container al-parent-centered al-width-75-pct">
                            <div class="al-child-centered" style="height: 50px">
                                <p class="al-descrizione-allerta">Grave pericolo: fenomeni ed effetti ingenti ed estesi.</p>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </dd>
        <dt></dt>
        <dd id="al-accordion-legenda-elem-neve-C" class="accordion-navigation ">
            <a href="#al-panel-neve-C">
                <div class="al-accordion-legenda-elem-header">
                    <h2>NEVE</h2>
                </div>
            </a>
            <div id="al-panel-neve-C" class="content  al-accordion-legenda-elem-body">
                <div class="al-container">
                    <div class="al-container al-livello-allerta" style="margin-top: 5px">
                        <div class="al-container left al-width-25-pct">
                            <div class="al-table-cell al-background-allerta-green">
                                <p>VERDE</p>
                            </div>
                        </div>
                        <div class="al-container al-parent-centered al-width-75-pct">
                            <div class="al-child-centered" style="height: 50px">
                                <p class="al-descrizione-allerta">Assenza o bassa probabilità a livello locale di fenomeni significativi prevedibili.</p>
                            </div>
                        </div>
                    </div>
                    <div class="al-container al-livello-allerta">
                        <div class="al-container left al-width-25-pct">
                            <div class="al-table-cell al-background-allerta-yellow">
                                <p>GIALLA</p>
                            </div>
                        </div>
                        <div class="al-container al-parent-centered al-width-75-pct">
                            <div class="al-child-centered" style="height: 50px">
                                <p class="al-descrizione-allerta">Disagio locale e problemi temporanei a viabilità.</p>
                            </div>
                        </div>
                    </div>
                    <div class="al-container al-livello-allerta">
                        <div class="al-container left al-width-25-pct">
                            <div class="al-table-cell al-background-allerta-orange">
                                <p>ARANCIONE</p>
                            </div>
                        </div>
                        <div class="al-container al-parent-centered al-width-75-pct">
                            <div class="al-child-centered" style="height: 50px">
                                <p class="al-descrizione-allerta">Disagio diffuso e problemi prolungati a viabilità.</p>
                            </div>
                        </div>
                    </div>
                    <div class="al-container al-livello-allerta">
                        <div class="al-container left al-width-25-pct">
                            <div class="al-table-cell al-background-allerta-red">
                                <p>ROSSA</p>
                            </div>
                        </div>
                        <div class="al-container al-parent-centered al-width-75-pct">
                            <div class="al-child-centered" style="height: 50px">
                                <p class="al-descrizione-allerta">Pericolo e problemi prolungati ed estesi a viabilità.</p>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </dd>
    </dl>
</div>    <div style="margin-top: 15px">
    <div class="al-container">
        <div class="al-container">
            <p class="al-text-bold">Simboli meteo</p>
        </div>
    </div>
</div>
<div class="al-container" style="margin-top: 5px">
    <div class="al-container-padded-right left al-width-33-pct al-parent-centered" style="text-align: center">
        <div class="al-child-centered" style="height: 31px; width: 48px; text-align: center">
            <img src="img/icone/nuvola_transparent.png" style="width: 37px" alt="Fenomeni significativi" title="Fenomeni significativi" />
        </div>
    </div>
    <div class="al-container-padded-right left al-width-33-pct al-parent-centered" style="text-align: center">
        <div class="al-child-centered" style="height: 31px; width: 48px; text-align: center">
            <img src="img/icone/nuvola_lightgray.png" style="width: 37px" alt="Fenomeni intensi" title="Fenomeni intensi" />
        </div>
    </div>
    <div class="al-container-padded-left right al-width-33-pct al-parent-centered" style="text-align: center">
        <div class="al-child-centered" style="height: 31px; width: 48px">
            <img src="img/icone/nuvola_darkgray.png" style="width: 37px" alt="Fenomeni molto intensi" title="Fenomeni molto intensi" />
        </div>
    </div>
</div>
<div class="al-container" style="margin-bottom: 10px">
    <div class="al-container-padded-right left al-width-33-pct">
        <p style="line-height: 0.75rem; font-size: 10px; text-align: center">Fenomeni significativi</p>
    </div>
    <div class="al-container-padded-right left al-width-33-pct">
        <p style="line-height: 0.75rem; font-size: 10px; text-align: center">Fenomeni intensi</p>
    </div>
    <div class="al-container-padded-left right al-width-33-pct">
        <p style="line-height: 0.75rem; font-size: 10px; text-align: center">Fenomeni molto intensi</p>
    </div>
</div>
<div class="al-container" style="margin-top: 15px">
    <div class="al-container right">
        
<div class="al-container">
    <a class="small button al-button-lightgray" target="_blank" href="docs/elenco_soglie_meteoidrologiche.pdf">
        <span class="al-button-caption">
            Scarica il PDF  
        </span>
        <span class="al-button-filesize">
             (0.47 MB)        </span>
        <img src="img/icone/pdf_icon_small.png"
             alt="Scarica il file in formato PDF"
             title="Scarica il file in formato PDF" />
    </a>
</div>    </div>
</div>    <div style="margin-top: 15px">
    <p><b>Divisione del territorio</b></p>
</div>
<div class="al-container" style="margin-top: 5px; height: 50px">
    <div class="al-container-padded-right left al-width-40-pct al-parent-centered" style="height: 100%">
        <div class="al-child-centered" style="height: 46px; width: 90px; text-align: center">
            <img src="img/icone/divisione_territorio.png" style="width: 90px" alt="Zone di allerta" title="Zone di allerta" />
        </div>
    </div>
    <div class="al-container-padded-left al-width-60-pct al-parent-centered" style="height: 100%">
        <div class="al-container al-child-centered right">
            <div class="al-container">
                <a class="small button al-button-lightgray"
                   href="divisione_territorio.php">Vai alla GUIDA</a>
            </div>
        </div>
    </div>
</div></div>            </div>
        </div>
    </div>
</dd>

<dt></dt>
<dd id="al-accordion-zone-elem-D" class="accordion-navigation al-position-relative">
    
    <div id="al-zona-D" class="al-position-absolute al-offset-down"></div>

            <div class="al-container al-accordion-zone-header al-background-allerta-lightgray">
            <div class="al-container left hide-for-small">
                <div class="al-container al-parent-centered al-accordion-zone-header-image left">
                    <div class="al-container al-child-centered">
                        <img src="img/mappe/AREA_D_V.png" alt="Zona D" title="Zona D" />
                    </div>
                </div>
            </div>
            <div class="al-container left hide-for-small">
                <div class="al-container al-parent-centered al-accordion-zone-header-title-zona left">
                    <div class="al-container al-child-centered al-text-horz-center">
                        <h3 class="al-display-inline al-color-white">zona </h3>
                    </div>
                </div>
            </div>
            <div class="al-container left">
                <div class="al-container al-parent-centered al-accordion-zone-header-title-cod-zona left">
                    <div class="al-container al-child-centered al-text-horz-center">
                        <h4 class="al-display-inline al-color-white">D</h4>
                    </div>
                </div>
            </div>
            <div class="al-container al-parent-centered al-accordion-zone-header-message left">
                <div class="al-container al-child-centered">
                    <h6 class="al-display-inline al-accordion-zone-header-message-font-size">Nessuna allerta</h6>
                </div>
            </div>
        </div>
        <div id="panelD" class="content">
        <div class="row">
            <div class="large-8 medium-8 small-12 columns">
                
                <!-- Dettaglio rischio meteo zona -->
                                <div class="al-container al-width-100-pct al-background-darkgray">
                    <div class="row">
                        <div class="large-12 medium-12 small-12 columns al-parent-centered al-accordion-zone-subheader-message left" style="height: 60px">
                            <div class="al-container al-child-centered" style="padding-left: 15px; padding-right: 15px">
                                <h1 class="al-color-white">ALTRI RISCHI METEO<!-- ZONA D--></h1>
                            </div>
                        </div>
                    </div>
                </div>
                <div class="row">
                    <div class="large-6 medium-6 small-12 columns">

                        <div class="al-container al-standard-panel">

                            <div class="al-container">
                                <div class="al-container" style="margin-bottom: 5px">
                                                                        <div class="al-container-padded-right left al-width-33-pct">
                                        <p style="text-align: center">Vento</p>
                                    </div>
                                                                    </div>
                                <div class="al-container">
                                                                        <div class="al-container-padded-right left al-width-33-pct">
                                        <div class="al-table-cell-icon">
                                            <img class="al-background-white" 
                                                 src="img/icone/VENTO_FORTE_N_BIANCO.png"
                                                 style="width: 48px; height: 48px"
                                                 alt="Vento forte n bianco"
                                                 title="Vento forte n bianco" />
                                        </div>
                                    </div>
                                                                    </div>

                                
                            </div>

                        </div>

                    </div>

                    <div class="large-6 medium-6 columns hide-for-small">



                    </div>
                </div>
                            </div>
            <div class="large-4 medium-4 hide-for-small columns">
                <div class="al-container al-legenda-detail-panel">
    <div class="al-container al-parent-centered al-width-100-pct">
        <div class="al-container al-child-centered al-width-50-pct">
            <p class="al-color-verydarkgray al-title">Legenda</p>
        </div>
        <div class="al-container al-child-centered al-width-50-pct">
            <a href="livelli_allerta_rischi.php"><h2 class="al-color-verydarkgray right">VAI ALLA GUIDA &gt;&gt;</h2></a>
        </div>
    </div>
    <div class="al-container">
    <p><b>Livelli allerta idrogeologica, idraulica e nivologica</b></p>
</div>
<div class="al-container al-accordion-legenda" style="margin-top: 5px">
    <dl class="accordion" data-accordion="">
        <dt></dt>
        <dd id="al-accordion-legenda-elem-temporali-D" class="accordion-navigation ">
            <a href="#al-panel-temporali-D">
                <div class="al-accordion-legenda-elem-header">
                    <h2>TEMPORALI</h2>
                </div>
            </a>
            <div id="al-panel-temporali-D" class="content  al-accordion-legenda-elem-body">
                <div class="al-container">
                    <div class="al-container al-livello-allerta" style="margin-top: 5px">
                        <div class="al-container left al-width-25-pct">
                            <div class="al-table-cell al-background-allerta-green">
                                <p>VERDE</p>
                            </div>
                        </div>
                        <div class="al-container al-parent-centered al-width-75-pct">
                            <div class="al-child-centered" style="height: 50px">
                                <p class="al-descrizione-allerta">Assenza o bassa probabilità a livello locale di fenomeni significativi prevedibili.</p>
                            </div>
                        </div>
                    </div>
                    <div class="al-container al-livello-allerta">
                        <div class="al-container left al-width-25-pct">
                            <div class="al-table-cell al-background-allerta-yellow">
                                <p>GIALLA</p>
                            </div>
                        </div>
                        <div class="al-container al-parent-centered al-width-75-pct">
                            <div class="al-child-centered" style="height: 50px">
                                <p class="al-descrizione-allerta">Occasionale pericolo: fenomeni puntuali anche intensi e repentini.</p>
                            </div>
                        </div>
                    </div>
                    <div class="al-container al-livello-allerta">
                        <div class="al-container left al-width-25-pct">
                            <div class="al-table-cell al-background-allerta-orange">
                                <p>ARANCIONE</p>
                            </div>
                        </div>
                        <div class="al-container al-parent-centered al-width-75-pct">
                            <div class="al-child-centered" style="height: 50px">
                                <p class="al-descrizione-allerta">Pericolo: massima gravità per fenomeni puntuali anche molto intensi, repentini e persistenti.</p>
                            </div>
                        </div>
                    </div>
                    <div class="al-container al-livello-allerta">
                        <div class="al-container left al-width-25-pct">
                            <div class="al-table-cell al-background-allerta-red">
                                <p>ROSSA</p>
                            </div>
                        </div>
                        <div class="al-container al-parent-centered al-width-75-pct">
                            <div class="al-child-centered" style="height: 50px">
                                <p class="al-descrizione-allerta">Codice non previsto per temporali (solo fenomeni estesi).</p>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </dd>
        <dt></dt>
        <dd id="al-accordion-legenda-elem-piogge-diffuse-D" class="accordion-navigation active">
            <a href="#al-panel-piogge-diffuse-D">
                <div class="al-accordion-legenda-elem-header">
                    <h2>PIOGGE DIFFUSE</h2>
                </div>
            </a>
            <div id="al-panel-piogge-diffuse-D" class="content active al-accordion-legenda-elem-body">
                <div class="al-container">
                    <div class="al-container al-livello-allerta" style="margin-top: 5px">
                        <div class="al-container left al-width-25-pct">
                            <div class="al-table-cell al-background-allerta-green">
                                <p>VERDE</p>
                            </div>
                        </div>
                        <div class="al-container al-parent-centered al-width-75-pct">
                            <div class="al-child-centered" style="height: 50px">
                                <p class="al-descrizione-allerta">Assenza o bassa probabilità a livello locale di fenomeni significativi prevedibili.</p>
                            </div>
                        </div>
                    </div>
                    <div class="al-container al-livello-allerta">
                        <div class="al-container left al-width-25-pct">
                            <div class="al-table-cell al-background-allerta-yellow">
                                <p>GIALLA</p>
                            </div>
                        </div>
                        <div class="al-container al-parent-centered al-width-75-pct">
                            <div class="al-child-centered" style="height: 50px">
                                <p class="al-descrizione-allerta">Occasionale pericolo: fenomeni ed effetti locali.</p>
                            </div>
                        </div>
                    </div>
                    <div class="al-container al-livello-allerta">
                        <div class="al-container left al-width-25-pct">
                            <div class="al-table-cell al-background-allerta-orange">
                                <p>ARANCIONE</p>
                            </div>
                        </div>
                        <div class="al-container al-parent-centered al-width-75-pct">
                            <div class="al-child-centered" style="height: 50px">
                                <p class="al-descrizione-allerta">Pericolo: fenomeni ed effetti diffusi.</p>
                            </div>
                        </div>
                    </div>
                    <div class="al-container al-livello-allerta">
                        <div class="al-container left al-width-25-pct">
                            <div class="al-table-cell al-background-allerta-red">
                                <p>ROSSA</p>
                            </div>
                        </div>
                        <div class="al-container al-parent-centered al-width-75-pct">
                            <div class="al-child-centered" style="height: 50px">
                                <p class="al-descrizione-allerta">Grave pericolo: fenomeni ed effetti ingenti ed estesi.</p>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </dd>
        <dt></dt>
        <dd id="al-accordion-legenda-elem-neve-D" class="accordion-navigation ">
            <a href="#al-panel-neve-D">
                <div class="al-accordion-legenda-elem-header">
                    <h2>NEVE</h2>
                </div>
            </a>
            <div id="al-panel-neve-D" class="content  al-accordion-legenda-elem-body">
                <div class="al-container">
                    <div class="al-container al-livello-allerta" style="margin-top: 5px">
                        <div class="al-container left al-width-25-pct">
                            <div class="al-table-cell al-background-allerta-green">
                                <p>VERDE</p>
                            </div>
                        </div>
                        <div class="al-container al-parent-centered al-width-75-pct">
                            <div class="al-child-centered" style="height: 50px">
                                <p class="al-descrizione-allerta">Assenza o bassa probabilità a livello locale di fenomeni significativi prevedibili.</p>
                            </div>
                        </div>
                    </div>
                    <div class="al-container al-livello-allerta">
                        <div class="al-container left al-width-25-pct">
                            <div class="al-table-cell al-background-allerta-yellow">
                                <p>GIALLA</p>
                            </div>
                        </div>
                        <div class="al-container al-parent-centered al-width-75-pct">
                            <div class="al-child-centered" style="height: 50px">
                                <p class="al-descrizione-allerta">Disagio locale e problemi temporanei a viabilità.</p>
                            </div>
                        </div>
                    </div>
                    <div class="al-container al-livello-allerta">
                        <div class="al-container left al-width-25-pct">
                            <div class="al-table-cell al-background-allerta-orange">
                                <p>ARANCIONE</p>
                            </div>
                        </div>
                        <div class="al-container al-parent-centered al-width-75-pct">
                            <div class="al-child-centered" style="height: 50px">
                                <p class="al-descrizione-allerta">Disagio diffuso e problemi prolungati a viabilità.</p>
                            </div>
                        </div>
                    </div>
                    <div class="al-container al-livello-allerta">
                        <div class="al-container left al-width-25-pct">
                            <div class="al-table-cell al-background-allerta-red">
                                <p>ROSSA</p>
                            </div>
                        </div>
                        <div class="al-container al-parent-centered al-width-75-pct">
                            <div class="al-child-centered" style="height: 50px">
                                <p class="al-descrizione-allerta">Pericolo e problemi prolungati ed estesi a viabilità.</p>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </dd>
    </dl>
</div>    <div style="margin-top: 15px">
    <div class="al-container">
        <div class="al-container">
            <p class="al-text-bold">Simboli meteo</p>
        </div>
    </div>
</div>
<div class="al-container" style="margin-top: 5px">
    <div class="al-container-padded-right left al-width-33-pct al-parent-centered" style="text-align: center">
        <div class="al-child-centered" style="height: 31px; width: 48px; text-align: center">
            <img src="img/icone/nuvola_transparent.png" style="width: 37px" alt="Fenomeni significativi" title="Fenomeni significativi" />
        </div>
    </div>
    <div class="al-container-padded-right left al-width-33-pct al-parent-centered" style="text-align: center">
        <div class="al-child-centered" style="height: 31px; width: 48px; text-align: center">
            <img src="img/icone/nuvola_lightgray.png" style="width: 37px" alt="Fenomeni intensi" title="Fenomeni intensi" />
        </div>
    </div>
    <div class="al-container-padded-left right al-width-33-pct al-parent-centered" style="text-align: center">
        <div class="al-child-centered" style="height: 31px; width: 48px">
            <img src="img/icone/nuvola_darkgray.png" style="width: 37px" alt="Fenomeni molto intensi" title="Fenomeni molto intensi" />
        </div>
    </div>
</div>
<div class="al-container" style="margin-bottom: 10px">
    <div class="al-container-padded-right left al-width-33-pct">
        <p style="line-height: 0.75rem; font-size: 10px; text-align: center">Fenomeni significativi</p>
    </div>
    <div class="al-container-padded-right left al-width-33-pct">
        <p style="line-height: 0.75rem; font-size: 10px; text-align: center">Fenomeni intensi</p>
    </div>
    <div class="al-container-padded-left right al-width-33-pct">
        <p style="line-height: 0.75rem; font-size: 10px; text-align: center">Fenomeni molto intensi</p>
    </div>
</div>
<div class="al-container" style="margin-top: 15px">
    <div class="al-container right">
        
<div class="al-container">
    <a class="small button al-button-lightgray" target="_blank" href="docs/elenco_soglie_meteoidrologiche.pdf">
        <span class="al-button-caption">
            Scarica il PDF  
        </span>
        <span class="al-button-filesize">
             (0.47 MB)        </span>
        <img src="img/icone/pdf_icon_small.png"
             alt="Scarica il file in formato PDF"
             title="Scarica il file in formato PDF" />
    </a>
</div>    </div>
</div>    <div style="margin-top: 15px">
    <p><b>Divisione del territorio</b></p>
</div>
<div class="al-container" style="margin-top: 5px; height: 50px">
    <div class="al-container-padded-right left al-width-40-pct al-parent-centered" style="height: 100%">
        <div class="al-child-centered" style="height: 46px; width: 90px; text-align: center">
            <img src="img/icone/divisione_territorio.png" style="width: 90px" alt="Zone di allerta" title="Zone di allerta" />
        </div>
    </div>
    <div class="al-container-padded-left al-width-60-pct al-parent-centered" style="height: 100%">
        <div class="al-container al-child-centered right">
            <div class="al-container">
                <a class="small button al-button-lightgray"
                   href="divisione_territorio.php">Vai alla GUIDA</a>
            </div>
        </div>
    </div>
</div></div>            </div>
        </div>
    </div>
</dd>

<dt></dt>
<dd id="al-accordion-zone-elem-E" class="accordion-navigation al-position-relative">
    
    <div id="al-zona-E" class="al-position-absolute al-offset-down"></div>

            <div class="al-container al-accordion-zone-header al-background-allerta-lightgray">
            <div class="al-container left hide-for-small">
                <div class="al-container al-parent-centered al-accordion-zone-header-image left">
                    <div class="al-container al-child-centered">
                        <img src="img/mappe/AREA_E_V.png" alt="Zona E" title="Zona E" />
                    </div>
                </div>
            </div>
            <div class="al-container left hide-for-small">
                <div class="al-container al-parent-centered al-accordion-zone-header-title-zona left">
                    <div class="al-container al-child-centered al-text-horz-center">
                        <h3 class="al-display-inline al-color-white">zona </h3>
                    </div>
                </div>
            </div>
            <div class="al-container left">
                <div class="al-container al-parent-centered al-accordion-zone-header-title-cod-zona left">
                    <div class="al-container al-child-centered al-text-horz-center">
                        <h4 class="al-display-inline al-color-white">E</h4>
                    </div>
                </div>
            </div>
            <div class="al-container al-parent-centered al-accordion-zone-header-message left">
                <div class="al-container al-child-centered">
                    <h6 class="al-display-inline al-accordion-zone-header-message-font-size">Nessuna allerta</h6>
                </div>
            </div>
        </div>
        <div id="panelE" class="content">
        <div class="row">
            <div class="large-8 medium-8 small-12 columns">
                
                <!-- Dettaglio rischio meteo zona -->
                                <div class="al-container al-width-100-pct al-background-darkgray">
                    <div class="row">
                        <div class="large-12 medium-12 small-12 columns al-parent-centered al-accordion-zone-subheader-message left" style="height: 60px">
                            <div class="al-container al-child-centered" style="padding-left: 15px; padding-right: 15px">
                                <h1 class="al-color-white">ALTRI RISCHI METEO<!-- ZONA E--></h1>
                            </div>
                        </div>
                    </div>
                </div>
                <div class="row">
                    <div class="large-6 medium-6 small-12 columns">

                        <div class="al-container al-standard-panel">

                            <div class="al-container">
                                <div class="al-container" style="margin-bottom: 5px">
                                                                        <div class="al-container-padded-right left al-width-33-pct">
                                        <p style="text-align: center">Vento</p>
                                    </div>
                                                                    </div>
                                <div class="al-container">
                                                                        <div class="al-container-padded-right left al-width-33-pct">
                                        <div class="al-table-cell-icon">
                                            <img class="al-background-white" 
                                                 src="img/icone/VENTO_FORTE_N_BIANCO.png"
                                                 style="width: 48px; height: 48px"
                                                 alt="Vento forte n bianco"
                                                 title="Vento forte n bianco" />
                                        </div>
                                    </div>
                                                                    </div>

                                
                            </div>

                        </div>

                    </div>

                    <div class="large-6 medium-6 columns hide-for-small">



                    </div>
                </div>
                            </div>
            <div class="large-4 medium-4 hide-for-small columns">
                <div class="al-container al-legenda-detail-panel">
    <div class="al-container al-parent-centered al-width-100-pct">
        <div class="al-container al-child-centered al-width-50-pct">
            <p class="al-color-verydarkgray al-title">Legenda</p>
        </div>
        <div class="al-container al-child-centered al-width-50-pct">
            <a href="livelli_allerta_rischi.php"><h2 class="al-color-verydarkgray right">VAI ALLA GUIDA &gt;&gt;</h2></a>
        </div>
    </div>
    <div class="al-container">
    <p><b>Livelli allerta idrogeologica, idraulica e nivologica</b></p>
</div>
<div class="al-container al-accordion-legenda" style="margin-top: 5px">
    <dl class="accordion" data-accordion="">
        <dt></dt>
        <dd id="al-accordion-legenda-elem-temporali-E" class="accordion-navigation ">
            <a href="#al-panel-temporali-E">
                <div class="al-accordion-legenda-elem-header">
                    <h2>TEMPORALI</h2>
                </div>
            </a>
            <div id="al-panel-temporali-E" class="content  al-accordion-legenda-elem-body">
                <div class="al-container">
                    <div class="al-container al-livello-allerta" style="margin-top: 5px">
                        <div class="al-container left al-width-25-pct">
                            <div class="al-table-cell al-background-allerta-green">
                                <p>VERDE</p>
                            </div>
                        </div>
                        <div class="al-container al-parent-centered al-width-75-pct">
                            <div class="al-child-centered" style="height: 50px">
                                <p class="al-descrizione-allerta">Assenza o bassa probabilità a livello locale di fenomeni significativi prevedibili.</p>
                            </div>
                        </div>
                    </div>
                    <div class="al-container al-livello-allerta">
                        <div class="al-container left al-width-25-pct">
                            <div class="al-table-cell al-background-allerta-yellow">
                                <p>GIALLA</p>
                            </div>
                        </div>
                        <div class="al-container al-parent-centered al-width-75-pct">
                            <div class="al-child-centered" style="height: 50px">
                                <p class="al-descrizione-allerta">Occasionale pericolo: fenomeni puntuali anche intensi e repentini.</p>
                            </div>
                        </div>
                    </div>
                    <div class="al-container al-livello-allerta">
                        <div class="al-container left al-width-25-pct">
                            <div class="al-table-cell al-background-allerta-orange">
                                <p>ARANCIONE</p>
                            </div>
                        </div>
                        <div class="al-container al-parent-centered al-width-75-pct">
                            <div class="al-child-centered" style="height: 50px">
                                <p class="al-descrizione-allerta">Pericolo: massima gravità per fenomeni puntuali anche molto intensi, repentini e persistenti.</p>
                            </div>
                        </div>
                    </div>
                    <div class="al-container al-livello-allerta">
                        <div class="al-container left al-width-25-pct">
                            <div class="al-table-cell al-background-allerta-red">
                                <p>ROSSA</p>
                            </div>
                        </div>
                        <div class="al-container al-parent-centered al-width-75-pct">
                            <div class="al-child-centered" style="height: 50px">
                                <p class="al-descrizione-allerta">Codice non previsto per temporali (solo fenomeni estesi).</p>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </dd>
        <dt></dt>
        <dd id="al-accordion-legenda-elem-piogge-diffuse-E" class="accordion-navigation active">
            <a href="#al-panel-piogge-diffuse-E">
                <div class="al-accordion-legenda-elem-header">
                    <h2>PIOGGE DIFFUSE</h2>
                </div>
            </a>
            <div id="al-panel-piogge-diffuse-E" class="content active al-accordion-legenda-elem-body">
                <div class="al-container">
                    <div class="al-container al-livello-allerta" style="margin-top: 5px">
                        <div class="al-container left al-width-25-pct">
                            <div class="al-table-cell al-background-allerta-green">
                                <p>VERDE</p>
                            </div>
                        </div>
                        <div class="al-container al-parent-centered al-width-75-pct">
                            <div class="al-child-centered" style="height: 50px">
                                <p class="al-descrizione-allerta">Assenza o bassa probabilità a livello locale di fenomeni significativi prevedibili.</p>
                            </div>
                        </div>
                    </div>
                    <div class="al-container al-livello-allerta">
                        <div class="al-container left al-width-25-pct">
                            <div class="al-table-cell al-background-allerta-yellow">
                                <p>GIALLA</p>
                            </div>
                        </div>
                        <div class="al-container al-parent-centered al-width-75-pct">
                            <div class="al-child-centered" style="height: 50px">
                                <p class="al-descrizione-allerta">Occasionale pericolo: fenomeni ed effetti locali.</p>
                            </div>
                        </div>
                    </div>
                    <div class="al-container al-livello-allerta">
                        <div class="al-container left al-width-25-pct">
                            <div class="al-table-cell al-background-allerta-orange">
                                <p>ARANCIONE</p>
                            </div>
                        </div>
                        <div class="al-container al-parent-centered al-width-75-pct">
                            <div class="al-child-centered" style="height: 50px">
                                <p class="al-descrizione-allerta">Pericolo: fenomeni ed effetti diffusi.</p>
                            </div>
                        </div>
                    </div>
                    <div class="al-container al-livello-allerta">
                        <div class="al-container left al-width-25-pct">
                            <div class="al-table-cell al-background-allerta-red">
                                <p>ROSSA</p>
                            </div>
                        </div>
                        <div class="al-container al-parent-centered al-width-75-pct">
                            <div class="al-child-centered" style="height: 50px">
                                <p class="al-descrizione-allerta">Grave pericolo: fenomeni ed effetti ingenti ed estesi.</p>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </dd>
        <dt></dt>
        <dd id="al-accordion-legenda-elem-neve-E" class="accordion-navigation ">
            <a href="#al-panel-neve-E">
                <div class="al-accordion-legenda-elem-header">
                    <h2>NEVE</h2>
                </div>
            </a>
            <div id="al-panel-neve-E" class="content  al-accordion-legenda-elem-body">
                <div class="al-container">
                    <div class="al-container al-livello-allerta" style="margin-top: 5px">
                        <div class="al-container left al-width-25-pct">
                            <div class="al-table-cell al-background-allerta-green">
                                <p>VERDE</p>
                            </div>
                        </div>
                        <div class="al-container al-parent-centered al-width-75-pct">
                            <div class="al-child-centered" style="height: 50px">
                                <p class="al-descrizione-allerta">Assenza o bassa probabilità a livello locale di fenomeni significativi prevedibili.</p>
                            </div>
                        </div>
                    </div>
                    <div class="al-container al-livello-allerta">
                        <div class="al-container left al-width-25-pct">
                            <div class="al-table-cell al-background-allerta-yellow">
                                <p>GIALLA</p>
                            </div>
                        </div>
                        <div class="al-container al-parent-centered al-width-75-pct">
                            <div class="al-child-centered" style="height: 50px">
                                <p class="al-descrizione-allerta">Disagio locale e problemi temporanei a viabilità.</p>
                            </div>
                        </div>
                    </div>
                    <div class="al-container al-livello-allerta">
                        <div class="al-container left al-width-25-pct">
                            <div class="al-table-cell al-background-allerta-orange">
                                <p>ARANCIONE</p>
                            </div>
                        </div>
                        <div class="al-container al-parent-centered al-width-75-pct">
                            <div class="al-child-centered" style="height: 50px">
                                <p class="al-descrizione-allerta">Disagio diffuso e problemi prolungati a viabilità.</p>
                            </div>
                        </div>
                    </div>
                    <div class="al-container al-livello-allerta">
                        <div class="al-container left al-width-25-pct">
                            <div class="al-table-cell al-background-allerta-red">
                                <p>ROSSA</p>
                            </div>
                        </div>
                        <div class="al-container al-parent-centered al-width-75-pct">
                            <div class="al-child-centered" style="height: 50px">
                                <p class="al-descrizione-allerta">Pericolo e problemi prolungati ed estesi a viabilità.</p>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </dd>
    </dl>
</div>    <div style="margin-top: 15px">
    <div class="al-container">
        <div class="al-container">
            <p class="al-text-bold">Simboli meteo</p>
        </div>
    </div>
</div>
<div class="al-container" style="margin-top: 5px">
    <div class="al-container-padded-right left al-width-33-pct al-parent-centered" style="text-align: center">
        <div class="al-child-centered" style="height: 31px; width: 48px; text-align: center">
            <img src="img/icone/nuvola_transparent.png" style="width: 37px" alt="Fenomeni significativi" title="Fenomeni significativi" />
        </div>
    </div>
    <div class="al-container-padded-right left al-width-33-pct al-parent-centered" style="text-align: center">
        <div class="al-child-centered" style="height: 31px; width: 48px; text-align: center">
            <img src="img/icone/nuvola_lightgray.png" style="width: 37px" alt="Fenomeni intensi" title="Fenomeni intensi" />
        </div>
    </div>
    <div class="al-container-padded-left right al-width-33-pct al-parent-centered" style="text-align: center">
        <div class="al-child-centered" style="height: 31px; width: 48px">
            <img src="img/icone/nuvola_darkgray.png" style="width: 37px" alt="Fenomeni molto intensi" title="Fenomeni molto intensi" />
        </div>
    </div>
</div>
<div class="al-container" style="margin-bottom: 10px">
    <div class="al-container-padded-right left al-width-33-pct">
        <p style="line-height: 0.75rem; font-size: 10px; text-align: center">Fenomeni significativi</p>
    </div>
    <div class="al-container-padded-right left al-width-33-pct">
        <p style="line-height: 0.75rem; font-size: 10px; text-align: center">Fenomeni intensi</p>
    </div>
    <div class="al-container-padded-left right al-width-33-pct">
        <p style="line-height: 0.75rem; font-size: 10px; text-align: center">Fenomeni molto intensi</p>
    </div>
</div>
<div class="al-container" style="margin-top: 15px">
    <div class="al-container right">
        
<div class="al-container">
    <a class="small button al-button-lightgray" target="_blank" href="docs/elenco_soglie_meteoidrologiche.pdf">
        <span class="al-button-caption">
            Scarica il PDF  
        </span>
        <span class="al-button-filesize">
             (0.47 MB)        </span>
        <img src="img/icone/pdf_icon_small.png"
             alt="Scarica il file in formato PDF"
             title="Scarica il file in formato PDF" />
    </a>
</div>    </div>
</div>    <div style="margin-top: 15px">
    <p><b>Divisione del territorio</b></p>
</div>
<div class="al-container" style="margin-top: 5px; height: 50px">
    <div class="al-container-padded-right left al-width-40-pct al-parent-centered" style="height: 100%">
        <div class="al-child-centered" style="height: 46px; width: 90px; text-align: center">
            <img src="img/icone/divisione_territorio.png" style="width: 90px" alt="Zone di allerta" title="Zone di allerta" />
        </div>
    </div>
    <div class="al-container-padded-left al-width-60-pct al-parent-centered" style="height: 100%">
        <div class="al-container al-child-centered right">
            <div class="al-container">
                <a class="small button al-button-lightgray"
                   href="divisione_territorio.php">Vai alla GUIDA</a>
            </div>
        </div>
    </div>
</div></div>            </div>
        </div>
    </div>
</dd>
                            </dl>
                        </div>
                    </div>
                </div>                
            </div>
        </div>

        <!-- Footer -->
<section class="al-footer-loghi">
    <div class="row">
        <div class="large-12 medium-12 small-12 columns">
            <p class="al-text-horz-center al-color-verydarkgray" style="margin-bottom: 15px">Sito realizzato con i fondi:</p>
        </div>
    </div>
    <div class="row">
        <div class="large-2 medium-2 columns hide-for-small" style="margin-top: 10px; margin-bottom: 20px">
            <div class="large-12 medium-12 columns">
                
            </div>
        </div>

        <div class="large-8 medium-8 columns" style="margin-top: 10px; margin-bottom: 20px">
            <div class="row" style="height: 120px">
                <div class="large-4 medium-4 columns al-text-horz-center">
                    <div class="al-container">
                        <img src="img/loghi/logo_fondo_europeo.png" 
                             alt="Fondo europeo di sviluppo regionale" title="Fondo europeo di sviluppo regionale" />
                    </div>
                </div>
                <div class="large-4 medium-4 columns al-text-horz-center">
                    <div class="show-for-small" style="height: 20px"></div>
                    <div class="al-container" style="margin-top: 7%">
                        <img src="img/loghi/logo_alcotra.png"
                             alt="ALCOTRA" title="ALCOTRA" />
                    </div>
                </div>
                <div class="large-4 medium-4 columns al-text-horz-center">
                    <div class="show-for-small" style="height: 40px"></div>
                    <div class="al-container">
                        <img src="img/loghi/logo_risknet.png"
                             alt="RiskNet" title="RiskNet" />
                    </div>
                </div>
            </div>
        </div>

        <div class="large-2 medium-2 columns hide-for-small" style="margin-top: 10px; margin-bottom: 20px">
            <div class="large-12 medium-12 columns">

            </div>
        </div>
    </div>
</section>
<section class="al-footer">
    <div class="row">
        <div class="large-12 medium-12 small-12 columns">
            <p class="al-text-horz-center al-color-white">REGIONE LIGURIA - Piazza De Ferrari 1 - 16121 Genova - P.IVA 00849050109 – WEB: <a href="http://www.regione.liguria.it" target="_blank">www.regione.liguria.it</a></p>
            <p class="al-text-horz-center al-color-white">ARPAL - Via Bombrini 8 - 16149 Genova -  P.IVA 01305930107 – WEB: <a href="http://www.arpal.gov.it" target="_blank">www.arpal.gov.it</a></p>
            <p class="al-text-horz-center al-color-white">© Tutti i diritti riservati</p>
        </div>
    </div>
</section>



<section class="al-footer al-footer-filler">
</section>
<section class="al-footer al-footer-sticky">
    <div class="row" style="height: 100%">
        <div class="large-12 medium-12 small-12 columns al-parent-centered" style="height: 100%">
            <p class="al-text-horz-center al-color-white al-child-centered">Sito web in costruzione, inviaci i tuoi commenti cliccando qui: <a href="mailto:info@proterina.eu">info@proterina.eu</a></p>
        </div>
    </div>
</section>

        <script type="text/javascript">
            $('.al-news-ticker').smarticker({
                    animation: 'slide',
                    controllerType: false,
                    category: false,
                    subcategory: true,
                    shadow: false,
                    speed: 1500
            });
            
            $(document).foundation();
        </script>
        
        <!-- Banner Cookie Law -->

    </body>

</html>
