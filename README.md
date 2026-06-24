# Mapa-interativo-do-turismo-rural-no-Cariri
Projeto de criação de um mapa interativo com os principais pontos de turismo rural da região do Cariri.
<!DOCTYPE html>
<html>
<head>
    
    <meta http-equiv="content-type" content="text/html; charset=UTF-8" />
    <script src="https://cdn.jsdelivr.net/npm/leaflet@1.9.3/dist/leaflet.js"></script>
    <script src="https://code.jquery.com/jquery-3.7.1.min.js"></script>
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.2.2/dist/js/bootstrap.bundle.min.js"></script>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/Leaflet.awesome-markers/2.0.2/leaflet.awesome-markers.js"></script>
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/leaflet@1.9.3/dist/leaflet.css"/>
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap@5.2.2/dist/css/bootstrap.min.css"/>
    <link rel="stylesheet" href="https://netdna.bootstrapcdn.com/bootstrap/3.0.0/css/bootstrap-glyphicons.css"/>
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/@fortawesome/fontawesome-free@6.2.0/css/all.min.css"/>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/Leaflet.awesome-markers/2.0.2/leaflet.awesome-markers.css"/>
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/python-visualization/folium/folium/templates/leaflet.awesome.rotate.min.css"/>
    
            <meta name="viewport" content="width=device-width,
                initial-scale=1.0, maximum-scale=1.0, user-scalable=no" />
            <style>
                #map_3e81bd200df6e89edada5780f319ea5e {
                    position: relative;
                    width: 100.0%;
                    height: 100.0%;
                    left: 0.0%;
                    top: 0.0%;
                }
                .leaflet-container { font-size: 1rem; }
            </style>

            <style>html, body {
                width: 100%;
                height: 100%;
                margin: 0;
                padding: 0;
            }
            </style>

            <style>#map {
                position:absolute;
                top:0;
                bottom:0;
                right:0;
                left:0;
                }
            </style>

            <script>
                L_NO_TOUCH = false;
                L_DISABLE_3D = false;
            </script>

        
</head>
<body>
    
    
            <div class="folium-map" id="map_3e81bd200df6e89edada5780f319ea5e" ></div>
        
</body>
<script>
    
    
            var map_3e81bd200df6e89edada5780f319ea5e = L.map(
                "map_3e81bd200df6e89edada5780f319ea5e",
                {
                    center: [-7.125368811833333, -39.481292501666665],
                    crs: L.CRS.EPSG3857,
                    ...{
  "zoom": 13,
  "zoomControl": true,
  "preferCanvas": false,
}

                }
            );

            

        
    
            var tile_layer_d77a9c75144aa1b5cd3ccf80b2cb76b6 = L.tileLayer(
                "https://tile.openstreetmap.org/{z}/{x}/{y}.png",
                {
  "minZoom": 0,
  "maxZoom": 19,
  "maxNativeZoom": 19,
  "noWrap": false,
  "attribution": "\u0026copy; \u003ca href=\"https://www.openstreetmap.org/copyright\"\u003eOpenStreetMap\u003c/a\u003e contributors",
  "subdomains": "abc",
  "detectRetina": false,
  "tms": false,
  "opacity": 1,
}

            );
        
    
            tile_layer_d77a9c75144aa1b5cd3ccf80b2cb76b6.addTo(map_3e81bd200df6e89edada5780f319ea5e);
        
    
            var marker_168f19389d7515eb23c6fc27c83ea24f = L.marker(
                [-7.044375, -39.3407],
                {
}
            ).addTo(map_3e81bd200df6e89edada5780f319ea5e);
        
    
        var popup_cd6a46b9119e3e8ae51eb59aad350336 = L.popup({
  "maxWidth": 200,
});

        
            
                var html_2e9b828d1cace316fbfd8143b2f69add = $(`<div id="html_2e9b828d1cace316fbfd8143b2f69add" style="width: 100.0%; height: 100.0%;">         <h4>Sistema Agroecológico Pe. Cícero</h4>         <p>Exemplo inspirador de convivência harmoniosa entre produção agrícola e conservação ambiental, com uma transformação de uma terra destinada ao cultivo de mandioca para uma agrofloresta diversificada. O espaço é ideal para visitas guiadas e atividades educativas que abordam agroecologia, sustentabilidade e biodiversidade, com contato com a naturea e refeições e lanches tradicionais.</p>         <img src="https://github.com/pablo2fp/Mapa-interativo-do-turismo-rural-no-Cariri/blob/main/Fotos%20turismo/zefa01.jpeg" width="150px">     </div>`)[0];
                popup_cd6a46b9119e3e8ae51eb59aad350336.setContent(html_2e9b828d1cace316fbfd8143b2f69add);
            
        

        marker_168f19389d7515eb23c6fc27c83ea24f.bindPopup(popup_cd6a46b9119e3e8ae51eb59aad350336)
        ;

        
    
    
            marker_168f19389d7515eb23c6fc27c83ea24f.bindTooltip(
                `<div>
                     Sistema Agroecológico Pe. Cícero
                 </div>`,
                {
  "sticky": true,
}
            );
        
    
            var marker_54eac911b348ceff4c883e8a74961e4c = L.marker(
                [-7.050485, -39.318634],
                {
}
            ).addTo(map_3e81bd200df6e89edada5780f319ea5e);
        
    
        var popup_84b324d75dece0e59287211721a536e4 = L.popup({
  "maxWidth": 200,
});

        
            
                var html_5bd55199c59b5493e75426f822e22f51 = $(`<div id="html_5bd55199c59b5493e75426f822e22f51" style="width: 100.0%; height: 100.0%;">         <h4>Associação Rural das Mulheres de  Caririaçu</h4>         <p>Nascido da união de mulheres comprometidas com a preservação ambiental, o fortalecimento comunitário e a geração de renda, a associação desenvolve um trabalho de artesado, fabricação de doces aproveitamento sustentável do católe, que é uma espécie abundante na região.</p>         <img src="https://github.com/pablo2fp/Mapa-interativo-do-turismo-rural-no-Cariri/blob/main/Fotos%20turismo/caririacu01.jpeg" width="150px">     </div>`)[0];
                popup_84b324d75dece0e59287211721a536e4.setContent(html_5bd55199c59b5493e75426f822e22f51);
            
        

        marker_54eac911b348ceff4c883e8a74961e4c.bindPopup(popup_84b324d75dece0e59287211721a536e4)
        ;

        
    
    
            marker_54eac911b348ceff4c883e8a74961e4c.bindTooltip(
                `<div>
                     Associação Rural das Mulheres de  Caririaçu
                 </div>`,
                {
  "sticky": true,
}
            );
        
    
            var marker_a39c2229fd9b4b0f1a11d51aca2bdb17 = L.marker(
                [-7.0732092, -39.6832737],
                {
}
            ).addTo(map_3e81bd200df6e89edada5780f319ea5e);
        
    
        var popup_ab4895483d2609414300586590701324 = L.popup({
  "maxWidth": 200,
});

        
            
                var html_973bd0772ed836d97a20493d4995cafe = $(`<div id="html_973bd0772ed836d97a20493d4995cafe" style="width: 100.0%; height: 100.0%;">         <h4>Pesqueiro do Sabino</h4>         <p>Pesqueiro do Sabino é um local ideal para momentos de paz, tranquilidade e boa gastronomia, com um ambiente familiar e agradável, voltado para desfrutar da prática da pesca recreativa e apreciação de uma bela paisagem rural. Além disso, a propriedade dispõe de uma diversidade de frutas, ideal para uma visita guiada e o serviço de colhe e pague.</p>         <img src="https://github.com/pablo2fp/Mapa-interativo-do-turismo-rural-no-Cariri/blob/main/Fotos%20turismo/Priscila01.jpeg" width="150px">     </div>`)[0];
                popup_ab4895483d2609414300586590701324.setContent(html_973bd0772ed836d97a20493d4995cafe);
            
        

        marker_a39c2229fd9b4b0f1a11d51aca2bdb17.bindPopup(popup_ab4895483d2609414300586590701324)
        ;

        
    
    
            marker_a39c2229fd9b4b0f1a11d51aca2bdb17.bindTooltip(
                `<div>
                     Pesqueiro do Sabino
                 </div>`,
                {
  "sticky": true,
}
            );
        
    
            var marker_19f3473086806272c938e1a164049a34 = L.marker(
                [-7.005191771, -39.73930621],
                {
}
            ).addTo(map_3e81bd200df6e89edada5780f319ea5e);
        
    
        var popup_766cdeb702faffc026e189fb8ac9bc00 = L.popup({
  "maxWidth": 200,
});

        
            
                var html_f583eacbdc9129c3b1cbb6f6df2afb88 = $(`<div id="html_f583eacbdc9129c3b1cbb6f6df2afb88" style="width: 100.0%; height: 100.0%;">         <h4>Sítio Dois Irmãos</h4>         <p>Resultado da dedicação do proprietário, o local é um exemplo de natureza e produção sustentável. Em uma área cuidadosamente manejada, os visitantes podem conhecer uma agrofloresta produtiva  que abriga uma impressinante plantação pitayas, além de diversas outras espécies cultivadas de forma integrada.</p>         <img src="https://github.com/pablo2fp/Mapa-interativo-do-turismo-rural-no-Cariri/blob/main/Fotos%20turismo/bel01%20(2).jpeg" width="150px">     </div>`)[0];
                popup_766cdeb702faffc026e189fb8ac9bc00.setContent(html_f583eacbdc9129c3b1cbb6f6df2afb88);
            
        

        marker_19f3473086806272c938e1a164049a34.bindPopup(popup_766cdeb702faffc026e189fb8ac9bc00)
        ;

        
    
    
            marker_19f3473086806272c938e1a164049a34.bindTooltip(
                `<div>
                     Sítio Dois Irmãos
                 </div>`,
                {
  "sticky": true,
}
            );
        
    
            var marker_6f00c7016776ab4612854c7cfe08db59 = L.marker(
                [-7.340465, -39.392127],
                {
}
            ).addTo(map_3e81bd200df6e89edada5780f319ea5e);
        
    
        var popup_550cab7e771364d5cd8518de2397f4cb = L.popup({
  "maxWidth": 200,
});

        
            
                var html_0d7e7d55de71d4ed68170290ae5018d5 = $(`<div id="html_0d7e7d55de71d4ed68170290ae5018d5" style="width: 100.0%; height: 100.0%;">         <h4>Sítio Nossa Roça</h4>         <p>Dedicado a valorização da vida no campo, o Sítio Nossa Roça ofecere aos visitantes visitas guiadas para vivenciar o contato com animais, pesque e pague conhecer práticas agroecológicas e o cotidiano da agricultura familiar. O espaço tem hospedagem e estrutura para realização de eventos.</p>         <img src="https://github.com/pablo2fp/Mapa-interativo-do-turismo-rural-no-Cariri/blob/main/Fotos%20turismo/elma01.jpeg" width="150px">     </div>`)[0];
                popup_550cab7e771364d5cd8518de2397f4cb.setContent(html_0d7e7d55de71d4ed68170290ae5018d5);
            
        

        marker_6f00c7016776ab4612854c7cfe08db59.bindPopup(popup_550cab7e771364d5cd8518de2397f4cb)
        ;

        
    
    
            marker_6f00c7016776ab4612854c7cfe08db59.bindTooltip(
                `<div>
                     Sítio Nossa Roça
                 </div>`,
                {
  "sticky": true,
}
            );
        
    
            var marker_cffb02a38d4440a6489022cda645147f = L.marker(
                [-7.2384869, -39.4137141],
                {
}
            ).addTo(map_3e81bd200df6e89edada5780f319ea5e);
        
    
        var popup_deea328fb70db14c05fa0557fc12dc5b = L.popup({
  "maxWidth": 200,
});

        
            
                var html_8b480eb6ee5f6407f2731185b198b19c = $(`<div id="html_8b480eb6ee5f6407f2731185b198b19c" style="width: 100.0%; height: 100.0%;">         <h4>Pedra de São Romão</h4>         <p>Em meio às belas paisagens do município de Altaneira, a Pedra de São Romão é um destino encantador para quem deseja vivenciiar a natureza, apreciar vistas deslmbrantes e conhecer a hospitalidade das familias rurais da regiao.</p>         <img src="https://github.com/pablo2fp/Mapa-interativo-do-turismo-rural-no-Cariri/blob/main/Fotos%20turismo/pedra01.jpeg" width="150px">     </div>`)[0];
                popup_deea328fb70db14c05fa0557fc12dc5b.setContent(html_8b480eb6ee5f6407f2731185b198b19c);
            
        

        marker_cffb02a38d4440a6489022cda645147f.bindPopup(popup_deea328fb70db14c05fa0557fc12dc5b)
        ;

        
    
    
            marker_cffb02a38d4440a6489022cda645147f.bindTooltip(
                `<div>
                     Pedra de São Romão
                 </div>`,
                {
  "sticky": true,
}
            );
        
</script>
</html>
