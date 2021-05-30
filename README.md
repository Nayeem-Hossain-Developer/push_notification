add jquery cdn or file link. like // <script src="https://cdnjs.cloudflare.com/ajax/libs/jquery/3.6.0/jquery.min.js"> </script>
add push.min.js and serviceWorker.min file link. //<script src="push.min.js"> </script>
<script src="serviceWorker.min"> </script>

then make a javascript function and write below code in that function.

<script type="text/javascript">
	function notification(){      // here notification is javascript function. you can give any name of this function as you wish.
		
		Push.create("Hello Nayeem", {    // here push.crearte default function you can't change this function name. wrirtr something instead of "Hellow Nayeem" that you want show in
    body: "How are you'?",                    push notification. 
    icon: 'person-icon.png',         //here how are you is push notification message you may any name or text instead of it.
    timeout: 4000,                    // 'person-icon.png' you will give image link instead of it.
    onClick: function () {          
        window.focus();
        this.close();
    }
});
	}
</script>
