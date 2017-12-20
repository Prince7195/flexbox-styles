#FLEXBOX: MDN(Mozilla Developer Network)

  #Property:

    #flex container:

        #display: flex or inline-flex;
        #flex-flow: flex-direction flex-wrap;
        #flex-direction: row, row-reverse, column, column-reverse;
        #flex-wrap: nowrap, wrap, wrap-reverse;
        #align-items: center, flex-start, flex-end; --- cross axis --- y(row) --- x(column)
        #justify-content: center, flex-start, flex-end; --- mainaxis --- x(row) --- y(column)
        #align-content: center;

    
    #flex items:
        #order: 0,1,2,.. any order number by default 0
        #align-self: center, flex-start, flex-end;
        #flex: flex-grow flex-shrink flex-basis