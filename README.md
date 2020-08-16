# homeworkWeek3
  function re(){     
        $.ajax({     
        type: "get",      
        url: "/home/news",      
        contentType : 'application/json'      
        }).then(function (e){       
            newsList = JSON.parse(e);     
            refreshUI();    
        })     
    }     
