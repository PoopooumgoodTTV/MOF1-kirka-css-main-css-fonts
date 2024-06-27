/* Fonts */
@font-face {
    font-family: gamefont;
    src: url("https://raw.githubusercontent.com/MOF1/krunker_css/main/css/fonts/Steradian-Bold.otf");
}

* {
    font-family: gamefont;
}

/* Text Color */
.level-value,
.levels,
.clan-tag,
.top-name,
.list-labels,
.active,
.level,
.header,
.lvl-leader,
.level-cont,
.label-primary,
.awards-span,
.champions-league,
.champions-scores,
.all-scores-label,
.stat-name,
.progress-level-value,
.player-level{
    color: #af51e6 !important;
}

/* Hide Logo */
.interface .logo {
    display: none;
}

/*	Ad Removal */
.ad-bottom,
.ad-left {
    visibility: hidden;
}

/* Background */
.pattern-bg,
.bg-radial {
    display: none;
}

.interface .background{
    background: #272727 !important;
}

.end-modal {
    background: #272727 !important;

}

.loading-scene .players .level {
    color: white;
}

/* Login/Signup*/
.auth-form {
    margin-left: 0 !important;
    background: rgba(55, 55, 55, .61) !important;
    backdrop-filter: blur(5px);
    border: none !important;
    border-left: none !important;
    border-right: none !important;
    box-shadow: none !important;
    border-bottom: 5px solid #ffffff1c !important;
    border-radius: 0 !important;
    width: 2500px !important;
    height: 118px !important;
}

.auth-form .btns button {
    transform: none !important;
    padding: 0px;
	left: -450%;
}

.auth-user .loading {
    background: rgba(55, 55, 55, .61);
	backdrop-filter: blur(5px);
	border: none;
	border-bottom: 5px solid #ffffff1c !important;
	border-radius: 0;
	width: 2500px;
    height: 118px !important;
}

.auth-user .loader-container {
	margin-right: 95% !important;
}

.button[data-v-02c36fca] {
    -webkit-text-stroke: 0px !important;
}

.auth-form button,
.auth-form button .border-top,
.auth-form button .border-bottom{
    background: transparent !important;
    box-shadow: none !important;
}

.auth-form button .triangle {
    display: none;
}

.auth-form .text {
    font-size: 26px !important;
}

.button[data-v-02c36fca]:after {
    border: none;
}

.left-interface .progress-label {
    display: none;
}

.left-interface .progress-lvl {
    margin-bottom: 20px;
}

.left-interface .progress-line {
    background: #4f4e4ead !important;
    height: 17px;
}

.left-interface .progress {
    background: -webkit-gradient(linear, left top, right top, from(#84a1ff), to(#39ffd4)) !important;
    background: linear-gradient(to right, #84a1ff, #39ffd4) !important;
}

.left-interface .level {
    color: white;
}

.left-interface .avatar-info,
.left-interface .user-info,
.left-interface .money {
    background: transparent !important;
	margin-left: -18px;
    bottom: 35px;
	border: none;
}

/* Left icons */
.left-icons {
    background: rgba(55, 55, 55, 0) !important;
    backdrop-filter: blur(5px);
    left: 0 !important;
    border: none !important;
}

.left-icons .icon-btn {
    background: transparent;
	border: none;
    width: 115px;
    border-radius: 0;
}

/* Right Interface */
.right-interface {
	padding-top: 20px;
}

.soc-group:nth-child(1),
.soc-group:nth-child(2) {
    background: transparent !important;
    border: none;
    visibility: hidden;
}

.right-interface .settings {
	background: transparent;
	border: none;
	width: 20px !important;
	transition: 0.3s;
} 

.right-interface .settings:hover {
	background: none;
	transform: scale(1.2);
}

.tab-header{
    background: transparent !important;
}

/* Daily Quest */
.quests,.quest {
	background: rgba(55, 55, 55, 0) !important;
    border: none !important;
    z-index: 2 !important;
}

.quest .progress-line {
	background: #4f4e4ead;
}

.rewards,.reward {
	background: #4f4e4ead !important;
}

.quest .progress2 {
	color: #87898c;
}

.quest .progress-line .progress {
	background: -webkit-gradient(linear, left top, right top, from(#84a1ff), to(#39ffd4)) !important;
    background: linear-gradient(to right, #84a1ff, #39ffd4) !important;
}

/* Container */
.container {
    background: #101216 !important;
    box-shadow: none !important;
    border-radius: 0 !important;
}

.container-card {
    background: #101216 !important;
    box-shadow: none !important;
    border: none !important;
    border-radius: 0 !important;
}

.container-card .close {
	display: none ;
}

.container-card .header {
	color: white;
}

.container-card .label {
	color: #87898c;
}

.container-card .button {
 	background: rgba(68, 68, 68, .45) !important;	
	box-shadow: none !important;
}

.container-card .border {
	display: none;
}

.loader  {
	background: transparent !important;
	border: none !important;
}

.background {
    background: transparent !important;
    border-radius: 0;
}

.tabs {
    background: transparent !important;
    border-bottom: none !important;
    box-shadow: none !important;
    border-right: none !important;
}

.tab {
    background: transparent !important;
    border-right: none !important;
    border-left: none !important;
}

.tab:hover,
.nav:hover {
	color: #39ffd4 !important;
}

.tab.active {
	color: #39ffd4;
	border-bottom: 3px solid #39ffd4;
}

.active-tab {
	color: #39ffd4 !important;
	border-bottom: 3px solid #39ffd4;
}

.nav.active {
	color: #39ffd4;
}

.head-text {
    background: transparent !important;
    box-shadow: none !important;
}

.add-friends,
.top-items {
    background: transparent !important;
}

.limit {
    border-left: none !important;
}

.top-bar,
.close[data-v-747e6ab9],
.home,
.name-page,
.select-mods-cont hr,
.info-icon,
.container button .border-top,
.container button .border-bottom {
    display: none !important;
}

.reset-time,
.info-awards,
.news {
    background: transparent !important;
    box-shadow: none !important;
}

.settings .box {
    background: transparent;
    border: none;
}

.select-mods-cont {
    border: none !important;
    border-radius: 0 !important;
    background: #101216 !important;
    overflow: visible;
}

.interface.text-2 > .play > div > .play-content-up > div > div > .select-mods-maps {
    text-align: left;
    width: 100% !important;
    height: 55% !important;
}

.select-regions-cont {
    border: none !important;
    border-radius: 0 !important;
    background: #101216 !important;
    margin-bottom: 40px;
    z-index: 1 !important;
}

.container button {
    background: rgb(68, 68, 68) !important;
    border-radius: 0 !important;
    transform: none !important;
}

.container button .border-top,
.container button .border-bottom {
    display: none;
}

.text {
    transform: none !important;
}

.settings .header,
.vm--container .cont .head {
	color: white !important;
}

.settings .label {
	color: #87898c ;
}

/* Profile */
.profile .statistics,
.profile .progress,
.profile .k-d,
.card-profile {
    background: transparent !important;
    box-shadow: none !important;
}

.profile .progress-line {
    background: #4f4e4ead;
}

.profile .progress-level-value,
.stat-name {
    color: white !important;
}

.profile .progress[data-v-5aafd15a] {
    background: -webkit-gradient(linear, left top, right top, from(#84a1ff), to(#39ffd4)) !important;
    background: linear-gradient(to right, #84a1ff, #39ffd4) !important;
}

.heads .levels {
    display: none;
}

.stat-value {
    color: #87898c !important;
}

.news img {
    border-radius: 0 !important;
}

.news .info {
    background: #101216 !important;
}

.news .info-content {
    background: #101216 !important;
}

.info h1 {
    background: #101216 !important;
}

.changelog-item {
    background: transparent !important;
    border: none !important;
}

/* Inventory */
.tab-bar,
.subject,
.inventory .left {
    background: transparent !important;
}

.subjects,
.gun {
    background: transparent !important;
    border: none !important;
}

.inventory .avatar-head {
    display: none;
}

.inventory .bottom {
    background: transparent !important;
    backdrop-filter: blur(2px) !important;
    background-image: linear-gradient(to left, #39ffd400, #39ffd417) !important;
}

/* Play Content */
.play-content .select-region,
.play-content .select-mod {
    background: rgba(55, 55, 55, 0);
    border-radius: 0;
    border: none !important;
}

.play-content .select-region:hover {
    background: rgba(55, 55, 55, .61);
    backdrop-filter: blur(5px);
}

.play-content .select-mod:hover {
    background: rgba(55, 55, 55, .61);
}

#play-btn {
    background: rgba(68, 68, 68, .45) !important;
    width: 360px;
    box-shadow: none !important;
    transform: none !important;
}

#play-btn:hover {
    background: #39ffd4bf !important;
}

#play-btn .border-top,
#play-btn .border-bottom {
    background: none !important;
}

.triangle[data-v-02c36fca] {
    display: none !important;
}

.lvl-leader {
    color: white !important;
}

.list-cont,
.list-champions,
.top-items .items .item,
.bottom-items .item,
.leaderboard-cont .items {
    background: transparent !important;
    box-shadow: none !important;
}

.list-players .top-items {
    box-shadow: none !important;
}

/* Clan */
.clans,
.clans .items .item,
.my-clan .list-container .list .item .item-content {
    background: transparent !important;
}

.my-clan .card-cont,
.my-clan .list-container,
.champions-list {
    background: transparent !important;
    box-shadow: none !important;
}

.my-clan .card-cont .name {
	color: #af51e6;
}

.my-clan .champions-league,
.my-clan .champions-scores,
.my-clan .all-scores-label {
	color: white !important;
}

.my-clan .champions-values,
.my-clan .all-scores-value,
.my-clan .description {
	color: #87898c;
}

/* Market */
.bottom-subj .count {
    background: transparent;
}

/* Esc Interface*/
.esc-interface {
    backdrop-filter: blur(5px);
}

.esc-interface .head-right button,
.esc-interface .head-right button .border-top,
.esc-interface .head-right button .border-bottom {
    background: #101216 !important;
    box-shadow: none;
    border-radius: 0;
}

.esc-interface .head-right button:hover {
    background: #101216 !important;
    border-bottom: 5px solid white;
}

.esc-interface .left-container .player {
    background: transparent;
    background-image: linear-gradient(to left, #39ffd408, #39ffd440) !important;
}

.esc-interface .right-container {
    background: transparent !important;
}

.esc-interface .primary {
	color: #39ffd4 !important;
}

.esc-interface .level{
	color: white;
}

.continue {
	background: rgb(68, 68, 68) !important;
	box-shadow: none !important;
}

.continue .border-top,
.continue .border-bottom {
	background: transparent !important;
	box-shadow: none !important;
}

/* HUD */
.mini-map-cont .name,
.desktop-game-interface .info-key-cont,
.mWwn,
.instruction,.quantity,
.list-weapons {
    display: none !important;
}

.endurance-progress {
	background: -webkit-gradient(linear, left top, right top, from(#84a1ff), to(#39ffd4)) !important;
    background: linear-gradient(to right, #84a1ff, #39ffd4) !important;
}

.ammunition {
    display: inline-block;
    position: fixed;
    left: calc(53% + 180px);
}

.kill-death {
    margin-top: 60px;
    margin-left: 2px;
}

.kill-death .kill,
.WwNWnmw.bg.text-1{
    background: transparent;
    box-shadow: none;
}

.state-cont .timer {
    position: fixed;
    top: 18px;
    background: transparent !important;
    box-shadow: none !important;
    font-size: 50px;
}

/* In Game Leaderboard */
.tab-info {
    background: rgba(55, 55, 55, .61) !important;
	box-shadow: none !important;
	border-radius: 0 !important;
	border: 5px solid #ffffff1c;
}

.tab-info .head {
	display: none;
}

.tab-info .player {
	background: transparent !important;	
}

.tab-info .primary {
	color: white !important;
}

.tab-info .nickname,
.tab-info .player-right {
	color: #87898c;
}

.tab-info .list {
	color: white;
	margin: 0 !important;
}

.tab-info .list .list-value:nth-child(1),
.tab-info .list .list-value:nth-child(2),
.tab-info .list .list-value:nth-child(3) {
	visibility: hidden;
}

.tab-info .list .list-value:nth-child(1):after {
	visibility: visible;
	content: "K";
	margin-left: -29px;
}

.tab-info .list .list-value:nth-child(2):after {
	visibility: visible;
	content: "D";
	margin-left: -28px;
}

.tab-info .list .list-value:nth-child(3):after {
	visibility: visible;
	content: "S";
	margin-left: -5px;
}

.tab-info .player-right svg {
	display: none;
}

.kill-bar-item {
	background: rgba(55, 55, 55, .61) !important;
	border: 3px solid red;
}

.kill-bar-item .name {
	color: #8badd6;
}

.kill-bar-item .name-kill {
	color: #f1c876;
}

/* Chat */
.chat {
    border-radius: 5px;
    -webkit-mask-image: linear-gradient(to bottom, transparent, black, black);
}

.chat .input-wrapper {
    top: 400px !important;
    width: 103%;
    height: 15px;
}

.chat .name {
    color: white;
}

.message{
    color: #87898c !important;
}

.message .lvl {
    color: #39ffd4;
}

/* End Screen */
.end-modal .bottom {
    display: none;
}

.end-modal .progress-line {
    background: #4f4e4ead;
}

.end-modal .progress {
    background: -webkit-gradient(linear, left top, right top, from(#84a1ff), to(#39ffd4)) !important;
    background: linear-gradient(to right, #84a1ff, #39ffd4) !important;
}

.end-modal .team-list-players .card-cont:nth-child(1),
.end-modal .team-list-players .card-cont:nth-child(2),
.end-modal .items {
    background: transparent !important;
    box-shadow: none !important;
}

.end-modal .team-list-players .label {
    background: transparent;
}

.end-modal .label-text,
.end-modal .points,
.end-modal .lvl-leader {
    color: white;
}

.end-modal .chat {
    margin-bottom: -53px;
    border-radius: 5px;
    -webkit-mask-image: linear-gradient(to bottom, transparent, black, black);
}

.end-modal .chat .input-wrapper {
    top: 400px !important;
    width: 103%;
    height: 130px;
}

.end-modal #WMNn {
    width: 310px;
    margin-left: 20px;
}

.end-modal .team-list-players .list .player {
    background: transparent;
}

/* Reward Container */
.progress[data-v-f1059abc],
.lvl[data-v-f1059abc],
.progress-helper {
    background: -webkit-gradient(linear, left top, right top, from(#84a1ff), to(#39ffd4)) !important;
    background: linear-gradient(to right, #84a1ff, #39ffd4) !important;
}

.buy-btn[data-v-f1059abc] {
	display: none !important;
}

.level-head {
    display: none !important;
}

.decor-bg {
	display: none;
}

/* Inputs */
.private-btn > span[data-v-730c0c40] {
	content: url(https://i.ibb.co/cyJnWN5/openlock.png);
	position: fixed;
	left: 36px;
	top: 70px;
    width: 43px;
}

input {
    background: #fff0 !important;
    color: #fff !important;
    border-radius: 10px !important;
}

.selected {
    background: #292e39;
}

.items {
    background: #292e39 !important;
    box-shadow: none !important;
}

.settings .input {
    background: transparent !important;
    border: none !important;
    box-shadow: none !important;
    color: white !important;
}

.copy button {
	background: rgba(55, 55, 55, .61) !important;
	box-shadow: none !important;
}

.copy .border {
	display: none;
}
