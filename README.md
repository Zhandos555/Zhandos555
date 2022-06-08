<svg fill="none" viewBox="0 0 900 750" width="900" height="750" xmlns="http://www.w3.org/2000/svg">
	<foreignObject width="100%" height="100%">
		<div xmlns="http://www.w3.org/1999/xhtml">
			<style>
				@keyframes gradientBackground {
					0% {
						background-position: 0% 50%;
					}
					50% {
						background-position: 100% 50%;
					}
					100% {
						background-position: 0% 50%;
					}
				}
				@keyframes mainHeaderAppear {
					0% {
				             transform: translateX(-20px);
				             opacity: 0;
					}
					100% {
					     transform: translateX(0);
				    	     opacity: 1;
					}
				}
			       @keyframes secondHeaderAppear {
					0% {
						transform: translateX(20px);
				    		opacity: 0;
					}
					100% {
						transform: translateX(0);
				    		opacity: 1;
					}
				}
				.container {
					font-family:
						system-ui,
						-apple-system,
						'Segoe UI',
						Roboto,
						Helvetica,
						Arial,
						sans-serif,
						'Apple Color Emoji',
						'Segoe UI Emoji';
					display: flex;
					flex-direction: column;
					align-items: center;
					justify-content: flex-start;
					margin: 0 auto;
					width: 100%;
					height: 1600px;
				}
				h1{
				  font-size: 25px
				  font-weight: 600;
				  animation:  mainHeaderAppear 1s ease;
				}
				h1 span{
				  display: inline-block;
				  animation:  waveHand 1s ease infinite;
				}
				h2{
				  margin: 20px 0;
			          animation:  secondHeaderAppear 1s ease;
				}
				@keyframes waveHand {
								0% {
									transform: rotate(5deg);
								}
								50% {
									transform: rotate(-5deg);
								}
				 100% {
									transform: rotate(5deg);
								}
							}
				.main_info__container{
				  width: 90%;
				  display: grid;
				  grid-template-rows: repeat(2,1fr);
				  grid-template-columns: repeat(3,1fr);
				  gap: 20px;
				  margin: 20px 0;
				}
				.block{
				  border-radius: 5px;
				  position: relative;
				  display: flex;
				  flex-direction: column;
				  justify-content: center;
				  align-items: flex-start;
				  padding: 10px;
				  color: #575757;
				  animation: appear 1s ease;
				}
				@keyframes appear {
								0% {
									transform: translateY(-20px);
				    opacity: 0;
								}
								100% {
									transform: translateY(0);
				    opacity: 1;
								}
							}
				.block p, h3{
				  margin: 2px 0;
				}
				.working_on{
				  background-color: #77B6EA;
				  color: white;
				}
				.learning{
				  background-color: #B1F786;
				}
				.contact_me{
				  background-color: #F3A77B;
				  color: white;
				}
				.feedback{
				  background-color: #F7F286;
				  text-align: left;
				}
				.terminal{
				  background-color: #EDEDED;
				}
				.laptop{
				  border: 2px solid #77B6EA;
				}
				.browser{
				  border: 2px solid #B1F786;
				}
				.ex_monitor{
				  border: 2px solid #F3A77B;
				}
				.editor{
				  border: 2px solid #F7F286;
				}
				.editor p{
				  display: flex;
				  justify-content: center;
				  align-items: center;
				}
				.editor img{
				  width: 20px;
				  margin-right: 5px;
				}
				.terminal_app{
				  border: 2px solid #EDEDED;
				}
			</style>
			<div class="container">
				<h1>Hi <span>👋</span>, I'm Zhandos Sembayev</h1>
				<h2>I'm a Frontend developer / web designer based in Kazakhstan, Almaty</h2>
				<div class="main_info__container">
				  <div class="block working_on">
				    <p>🔭 Currently working on</p>
				    <h3>Spotify Clone </h3>
				  </div>
				  <div class="block learning">
				    <p>🌱 I'm currently learning</p>
				    <h3>VueJS</h3>
				  </div>
				  <div class="block contact_me">
				    <p>📫 How to reach me</p>
				    <h3>sembayev.zhandos@gmail.com</h3>
				  </div>
				  <div class="block feedback">
				    <h3>🤔 Feel free to give me feedback on my projects!</h3>
				  </div>
				</div>
				<h2>🧰 My Setup</h2>
				<div class="main_info__container">
				  <div class="block laptop">
				    <p>💻 Laptop</p>
				    <h3>Macbook Pro 16" </h3>
				  </div>
				  <div class="block browser">
				    <p>🌐 Browser</p>
				    <h3>Safari/Chrome</h3>
				  </div>
				  <div class="block ex_monitor">
				    <p>🖥 External Monitor</p>
				    <h3>HP Z38c</h3>
				  </div>
				  <div class="block editor">
				    <p> Code Editor</p>
				    <h3>VSCode</h3>
				  </div>
				  <div class="block terminal_app">
				    <p>👩‍💻 Terminal</p>
				    <h3>Hyper</h3>
				  </div>
			        </div>
			      <h2>🛠 Languages and Tools</h2>
		      </div>
		</div>
	</foreignObject>
</svg>
