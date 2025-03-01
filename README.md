*{
    margin: 0;
    padding: 0;
}
body{
    background-color: #548687;
    text-align: center;
}
.container{
    height: 70vh;
    display: flex;

    justify-content: center;
    align-items: center;

}
.game{
    height: 60vmin;
    width: 60vmin;
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
    align-items: center;
    gap: 1.5vmin;
}
.box{
    height: 18vmin;
    width: 18vmin;
    border-radius: 1rem;
    border: none;
    box-shadow: 0 0 1rem rgba(0, 0, 0, 1);
    font-size: 8vmin;
    color: red;
    background-color: #fffc7f;
}
#reset-btn{
    padding: 1rem;
    font-size: 1.25rem;
    background-color: black;
    color: white;
    border-radius: 1rem;
    border: none;
}
#new-btn{
    padding: 1rem;
    font-size: 1.25rem;
    background-color: black;
    color: white;
    border-radius: 1rem;
    border: none;

}
#msg{
    color: brown;
    font-size: 5vmin;

}
.msg-container{
    height: 100vmin;
    display: flex;
    justify-content: center;
    align-items: center;
    flex-direction: column;
    gap: 4rem;

    
}
.hide{
    display: none;
}
