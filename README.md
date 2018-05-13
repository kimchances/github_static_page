 $.ajax({
        url: "webAction.do",
        type: 'POST',
        dataType: 'JSON',
        data: {"serverCode":"getIndexCategory"},
        async: false, //同步才能return
    }).done(function(data) { //done代替success
        console.info(data):
    });