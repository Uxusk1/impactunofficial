 <style>
      .button {
        display: inline-block;
        border-radius: 4px;
        background-color: #90EE90;
        border: none;
        color: #FFFFFF;
        text-align: center;
        font-size: 28px;
        padding: 10px;
        width: 150px;
        transition: all 0.5s;
        cursor: pointer;
        margin: 5px;
      }

      .button span {
        cursor: pointer;
        display: inline-block;
        position: relative;
        transition: 0.5s;
      }

      .button span:after {
        content: '\00bb';
        position: absolute;
        opacity: 0;
        top: 0;
        right: -20px;
        transition: 0.5s;
      }

      .button:hover span {
        padding-right: 25px;
      }

      .button:hover span:after {
        opacity: 1;
        right: 0;
      }
    </style>
    
<h4>welcome to uxcrabdev's directory</h4>
<a href=exploits.html><button class="button" style="vertical-align:middle"><span>Foods</span></button><a>
