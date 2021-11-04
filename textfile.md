<!-- add single customize marker -->

 var marker=new google.maps.Marker({
                position:{lat:8.1965,lng:77.2355},
                map:map,
            })
            var infowindow=new google.maps.InfoWindow({
                content:"<h1>Alanchi</h1>"
            });
            marker.addListener('click',function(){
                infowindow.open(map,marker);
            })


        <!-- addmarker -->

             addMarker({
                 coords:{lat:8.1965,lng:77.2355},
                content:"<h2>Alanchi</h2>"});
             addMarker({coords:{lat:8.5241,lng: 76.9366},
            content:"<h2>Thiruvanthapuram</h2>"});
             addMarker({coords:{lat:8.1786,lng: 77.2561}});