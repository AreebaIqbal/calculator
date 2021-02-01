
function getNumber(num){

    var res = document.getElementById("res");
    res.value += num;
}

function clearAll(){

    var res = document.getElementById("res");
    res.value = "";
}

function getRes(){

    var res = document.getElementById("res");
    res.value = eval(res.value);
}