/*
i do not care and life sucks
  
Background Img: https://wpblink.com/sites/default/files/wallpaper/anime/66761/sword-art-online-ii-wallpapers-hd-66761-327252.png 
Transparency2 Module: https://raw.githack.com/Ruben7173/Ruben7173.github.io/master/BetterDiscord-Themes/Modules/transparency2.css - By Ruben7173#5048

The 2 items above are not owned by me, They go to there respected owners
*/

:root{
    --background: url('https://images.alphacoders.com/632/632525.png');
    --activetext-colour: white;

    --primary1-colour: red;
    --primary2-colour: rgba(255,0,0,0.5);
    --primary3-colour: rgba(100,0,0,0.6);

    --secondary1-colour: rgba(50,50,50,0.3);
    --secondary2-colour: rgba(100,100,100,0.5);
    --secondary3-colour: rgba(0,0,0,0.5);

    --transparency-1: linear-gradient(to right, rgba(0,0,0,0.5), rgba(0,0,0,0.5));
	--transparency-2: linear-gradient(to right, rgba(0,0,0,0.5), rgba(0,0,0,0.5));
	--transparency-3: linear-gradient(to right, rgba(0,0,0,0.5), rgba(0,0,0,0.5));
	--transparency-4: linear-gradient(to right, rgba(0,0,0,0.5), rgba(0,0,0,0.5));
    --transparency-5: linear-gradient(to right, rgba(0,0,0,0.5), rgba(0,0,0,0.5));
}

/*--------------------------------------------------------*/
	#app-mount {
		background: var(--background-image);
	}
	
	/* removing backgrounds */

	/* Guild and Top bar transparency */
	.theme-dark .wrapper-1_HaEi {
		background:transparent;
		background-image: var(--transparency-1);
	}
	
	/* transparency for channels and members list and private channels and left side of settings*/
	.container-1NXEtd, .privateChannels-oVe7HL, .app-3xd6d0 .standardSidebarView-E9Pc3j, .app-3xd6d0 .container-2cd8Mz {
		background: transparent;
		background-image: var(--transparency-2);
	}
	.theme-dark .panels-3wFtMD, .theme-light .panels-3wFtMD {
		background: var(--transparency-2);
	}
	/* chat and top area and other secondary pages */
	.app-3xd6d0 .chat-2ZfjoI, .app-3xd6d0 .scrollableContainer-15eg7h {
		background: transparent;
		background-image: var(--transparency-3);
	}
	/* removing color from specific class */
	.panels-j1Uci_ {
		background-color: transparent;
	}
	/* extra for transparency 3 special case */
	.themeDark-3Ap_7i, .app-3xd6d0 .chat-3bRxxu {
		background-color: transparent;
		background-image: var(--transparency-3);
	}
	.typeWindows-2-g3UY {
		background-image: var(--transparency-5);
	}
	/* removes margin from top area and adds it to the nav buttons + discord logo */
	.typeWindows-2-g3UY {
		height: 21px;
		margin-top: 0px;
	}
	/* removes a border under better discord at channels */
	.unread-1xRYoj {
		display:none;
	}
	/* fixes */
	.theme-dark {
		--background-primary: none;
		--background-secondary: none;
		--background-tertiary: none;
		--background-accent: none;
	} 
/*--------------------------------------------------------*/

/*Theme Itself*/
	/*Background Img*/
	#app-mount,
	#app-mount .container-16j22k {
		background-image: var(--background); 
		background-position: center; 
		background-size: cover; 
	}

	/*Home*/
	#app-mount .container-1r6BKw {background: transparent;}
 
	#app-mount .itemCard-v9viV7,
	#app-mount .popout-38lTFE {
		background-color: var(--secondary3-colour)
	}
	#app-mount .itemCard-v9viV7:hover, 
	#app-mount .itemCard-v9viV7.active-1xchHY {
		background-color: var(--secondary2-colour);
	}
	#app-mount .body-1ld4H7 {background-color: var(--secondary1-colour);}

	#app-mount .item-3HknzM[aria-label="Add Friend"] {background-color: var(--primary1-colour)!important}
	#app-mount .item-3HknzM[style*="rgba(67, 181, 129, 0.2)"] {background-color: var(--primary2-colour)!important; color: var(--primary1-colour)!important;}

	#app-mount .container-1D34oG {
		background-color: transparent;
		background-image: var(--transparency-1)
	}

	#app-mount .wrapper-2qzCYF {background: transparent; border-bottom: 2px solid var(--primary3-colour);}
	#app-mount .centerButton-3CaNcJ {background-color: var(--secondary1-colour)}
	#app-mount .leaveButton-2YnTyt {background-color: var(--primary3-colour);}

	/*Servers*/
	#app-mount .wrapper-1BJsBx.selected-bZ3Lue .childWrapper-anI2G9 {background-color: var(--primary3-colour)}
	#app-mount .wrapper-3NnKdC {background-color: var(--secondary3-colour);}
	#app-mount .wrapper-1BJsBx .childWrapper-anI2G9 {
		background-color: var(--primary3-colour); 
		color: var(--activetext-colour);
	}

	#app-mount .circleIconButton-jET_ig {background-color: var(--secondary2-colour); color: var(--activetext-colour);}
	#app-mount .circleIconButton-jET_ig:hover {background-color: var(--primary3-colour)!important;}


	#app-mount .numberBadge-2s8kKX {background-color: var(--primary1-colour)!important}

	#app-mount #bd-pub-li .wrapper-25eVIn {background-color: var(--secondary1-colour)}

	.folder .wrapper-1BJsBx {background-color: var(--secondary2-colour)!important; transition: background-color .15s ease-out;}
	.folder .wrapper-1BJsBx:hover {background-color: var(--primary3-colour)!important;}

	#app-mount .folder-21wGz3 {background-color: transparent;}
	#app-mount .expandedFolderBackground-1cujaW {background-color: var(--secondary1-colour);}
	#app-mount .expandedFolderBackground-1cujaW.collapsed-2ZrjoL {
		background-color: transparent; 
		transition: background-color .15s ease-out;
	}
		/*Server Boosting*/
		#app-mount .perksModal-fSYqOq {background: var(--transparency-1);}

		#app-mount .ctaBar-2UsjF2 {background-color: var(--secondary1-colour); border-radius: 8px}
		#app-mount .tierMarkerBackground-3q29am {background-color: transparent;}

		#app-mount .carouselItemSelected-JFUsnG .tierBody-16Chc9 {background-color: var(--secondary1-colour);}
		#app-mount .perk-2WeBWW {background-color: var(--secondary1-colour);}
			/*ServerMenu*/
			#app-mount .tierHeaderLocked-1a2opw {background-color: var(--secondary3-colour);}
			#app-mount .tierBody-x9kBBp {background-color: var(--secondary1-colour);}


		/*Channels*/
		#app-mount .containerDefault-3tr_sE {
			background-color: var(--primary3-colour); 
			height: 30px; text-align: center; 
			border-radius: 10px; 
			padding: 5px 5px 0 5px;
		}
		#app-mount .container-3w7J-x,
		#app-mount .activityPanel-28dQGo {
			background-image: var(--transparency-1); 
			background-color: rgba(0,0,0,0); 
			margin-bottom: 0;
		}

		#app-mount .containerDefault-3tr_sE {margin-top: 15px;}
		#app-mount .unreadBar-3YD_k9 {background-color: var(--primary1-colour);}
		#app-mount .containerDefault--pIXnN {margin-right: 10px;}


			/*Text*/
			#app-mount .containerDefault--pIXnN .content-1x5b-n:hover {width: 100%;}
			#app-mount .containerDefault--pIXnN.selected-3LIHYU .content-1x5b-n {width: 100%;}
			#app-mount .content-1x5b-n { background-color: var(--secondary1-colour) }
			#app-mount .content-1x5b-n:hover,
			#app-mount .containerDefault--pIXnN.selected-3LIHYU  .content-1x5b-n { background-color: var(--secondary2-colour)}
			#app-mount .containerDefault--pIXnN .content-1x5b-n{
				width: 190px; 
				transition: width 0.2s; 
				transition-timing-function: ease-in-out; 
			}

			#app-mount .containerDefault--pIXnN .modeMuted-onO3r- div.content-1x5b-n {background-color: var(--primary3-colour);}

				/*Embeds*/
				#app-mount .embedFull-2tM8-- {
					background-color: var(--secondary1-colour); 
					border-left: 4px solid;
					border-right: 4px solid;
					border-radius: 10px!important;
				}


			/*Voice*/
			#app-mount .containerDefault--pIXnN .modeConnected-3IsKId div.content-1x5b-n {width: 100%; background-color: var(--secondary2-colour);}
			#app-mount .containerDefault--pIXnN .modeLocked-25wLHj div.content-1x5b-n {background-color: var(--primary3-colour);}

				/*VC Info*/
				#app-mount .panels-j1Uci_ {background-color: transparent;}
				#app-mount .container-1giJp5 {background-color: var(--secondary3-colour);}
				#app-mount .button-14-BFJ[aria-label="Disconnect"] {background-color: var(--primary3-colour);}
				#app-mount .button-14-BFJ[aria-label="Disconnect"]:hover {background-color: var(--primary3-colour);}

				/*VC User*/
				#app-mount .list-2bwCXU { padding-left: 10px; }
				#app-mount .avatarSpeaking-3MqCHL {box-shadow:0 0 0 2px var(--primary1-colour); }

				#app-mount .voiceUser-14U_Ns .content-3xS9Lh:hover {background-color: transparent;}
				#app-mount .voiceUser-14U_Ns {
					transition: margin 0.2s; 
					transition-timing-function: ease-in-out; 
					margin-left: 0; 
					padding-right: 5px
				}
				#app-mount .voiceUser-14U_Ns:hover {
					background-color: var(--secondary1-colour); 
					border-radius: 2px; margin-left: 20px;
				}

				/*Live Feed*/
				#app-mount .root-25RxKh, 
				#app-mount .container-2oTpPc {
					background: var(--transparency-1);
				}

				#app-mount .mediaBarProgress-1xaPtl, 
				#app-mount .volumeSlider-XQocF6 div::before, 
				#app-mount .mediaBarWrapper-3D7r67 div::after, 
				#app-mount .mediaBarGrabber-1FqnbN {
					background-color: var(--primary1-colour);
				}

		/*Messages*/
		#app-mount .hasMore-3e72_v {background-color: var(--secondary1-colour); color: var(--primary1-colour);}
		#app-mount code {background-color: var(--secondary1-colour)}

		#app-mount .wrapperHover-1GktnT, 
		#app-mount .mention {
			background-color: var(--primary3-colour); 
			color: var(--primary1-colour);
		}
		#app-mount .mentioned-xhSam7 {background-color: transparent;}
		#app-mount .mentioned-xhSam7 .contents-2mQqc9, 
		#app-mount .mentioned-xhSam7 .container-1ov-mD {
			background-color: var(--primary3-colour);
		}
		#app-mount .mentioned-xhSam7:before {
			background: var(--primary1-colour); 
			width: 3px;
			margin-left: 72px;
		}

		#app-mount .messageGroupBlocked-3wrQQX {background-color: var(--secondary1-colour);}
		#app-mount .messageGroupBlockedBtn-1PBBh- {color: var(--primary1-colour);}

		#app-mount a.anchor-3Z-8Bb {color: var(--primary1-colour);}
		#app-mount .unreadMentionsBar-1VrBNe {background-color: var(--primary1-colour);}
		#app-mount .channelTextArea-rNsIhG .scrollableContainer-15eg7h {background-color: var(--secondary1-colour);}

		#app-mount .newMessagesBar-265mhP {background-color: var(--primary1-colour)} 

		#app-mount .buttons-cl5qTG .wrapper-2aW0bm {background-color: var(--secondary1-colour);}
		#app-mount .message-2qnXI6 {
			padding-top: 0;
			padding-bottom: 0;
		}


		#app-mount .contents-2mQqc9 img {margin-top: 0px;}
		#app-mount .contents-2mQqc9,
		#app-mount .container-1ov-mD {
			background-color: var(--secondary1-colour);
			padding: 0px 0 5px 10px;
		}
		#app-mount .header-23xsNx{
			padding-top: 5px;
		}


	/*ScrollBars*/
	#app-mount ::-webkit-scrollbar-thumb {background-color: var(--primary2-colour); border-color: transparent;}

	#app-mount .scrollerWrap-2lJEkd ::-webkit-scrollbar-track-piece {
		background-color: transparent; 
		border-color: transparent;
	}

	#app-mount .messagesWrapper-1sRNjr ::-webkit-scrollbar-track-piece, 
	#app-mount .peopleColumn-29fq28 ::-webkit-scrollbar-track-piece, 
	#app-mount .homeWrapperNormal-2KSUEa ::-webkit-scrollbar-track-piece {
		background-color: transparent; 
		border-color: transparent;
	}
	#app-mount .messagesWrapper-1sRNjr ::-webkit-scrollbar-track, 
	#app-mount .peopleColumn-29fq28 ::-webkit-scrollbar-track, 
	#app-mount .homeWrapperNormal-2KSUEa ::-webkit-scrollbar-track {
		background-color: var(--primary3-colour); 
		border-radius: 10px; 
		border-color: var(--primary3-colour)
	}

	/*Context Menu & Server Menu*/
	#app-mount .contextMenu-HLZMGh .barFill-23-gu- {background-color: var(--primary1-colour);}
	#app-mount .menu-Sp6bN1, #app-mount .contextMenu-HLZMGh {background-color: var(--secondary3-colour)}
	#app-mount .item-1GzJrl:hover , #app-mount .item-1Yvehc:hover {background-color: var(--secondary1-colour)}
	#app-mount .separator-2zcjq8 {background-color: var(--primary3-colour)}

	#app-mount .danger-2dXSTE:hover {background-color: var(--primary3-colour)}
	#app-mount input[type=checkbox]:checked+span {
		border-color:var(--primary1-colour); 
		background-color:var(--primary1-colour)
	}

	#app-mount .leave-1DRJfn:hover {background-color: var(--primary3-colour);}
	#app-mount .invite-271nFU:hover {background-color: rgba(114,137,218,0.5);}

	/*Server Members*/
	#app-mount .member-3-YXUe .layout-2DM8Md {
		margin-left: 30px;
		transition: margin-left 0.2s;
		transition-timing-function: ease-in-out;
		border-radius: 10px;
	}
	#app-mount .layout-2DM8Md:hover { margin-left: 8px; background-color: var(--secondary1-colour);}
	#app-mount .selected-aXhQR6 .layout-2DM8Md { margin-left: 8px; background-color: var(--secondary2-colour);}

	#app-mount .membersGroup-v9BXpm span {color: var(--activetext-colour);}
	#app-mount .membersGroup-v9BXpm {
		background-color: var(--primary3-colour);

		border: 2px solid var(--primary3-colour);
		border-radius: 8px;

		height: 20px;
		padding: 0 0 0 10px;
		margin: 15px 8px 0 16px;
	}

	/*Settings*/
	#app-mount .sidebar-CFHs9e .side-8zPYf6 .item-PXvHYJ, 
	#app-mount .ui-tab-bar-item {
		line-height:15px; 
		background-color: var(--secondary1-colour); 
		width: 100%; 
		transition: width 0.2s; 
		transition-timing-function: ease-in-out;
	}
	#app-mount .sidebar-CFHs9e .side-8zPYf6 .item-PXvHYJ:hover, 
	#app-mount .ui-tab-bar-item:hover {
		background-color: var(--secondary2-colour); 
		width:187px;
	}
	#app-mount .sidebar-CFHs9e .side-8zPYf6 .selected-3s45Ha, 
	#app-mount .ui-tab-bar-item.selected {
		line-height:15px; 
		background-color: var(--secondary2-colour)!important; 
		width:187px;
	}
	#app-mount .sidebar-CFHs9e .side-8zPYf6 .header-2RyJ0Y, 
	#app-mount .ui-tab-bar-header {
		background-color: var(--primary3-colour); 
		border-radius: 3px; 
		line-height:28px; 
		padding:0 0 0 10px
	}
	#app-mount .ui-tab-bar-item {margin-bottom: 2px}

	#app-mount .sidebar-CFHs9e {padding: 20px 18px 20px 23px ;width: 210px }
	#app-mount .sidebarRegion-VFTUkN {flex: 0}
	#app-mount .contentColumn-2hrIYH {max-width: 90%;padding: 60px 30px 80px}

		/*User Settings*/
		#app-mount .control-2BBjec .container-3auIfb svg[fill="none"] path{
			fill: var(--primary1-colour)
		}

		#app-mount .lookFilled-1Gx00P, 
		#app-mount .control-2BBjec .container-3auIfb, 

		#app-mount .bd-button,
		#app-mount .bd-switch-checked,
		#app-mount .bd-pfbtn,

		#app-mount .flexChild-faoVW3 .barFill-23-gu-, 
		#app-mount .item-PXvHYJ[style*="background-color: rgb(114, 137, 218)"] {
			background-color: var(--primary1-colour)!important;
		}


		#app-mount .item-26Dhrx circle {fill: var(--primary1-colour)}
		#app-mount .item-26Dhrx {background-color: var(--secondary1-colour)} 
		#app-mount .item-26Dhrx[tabindex="0"] {background-color: var(--secondary2-colour)}

		#app-mount .item-26Dhrx .title-3BE6m5 {margin-top: 1px;}

		#app-mount .game-1ipmAa:before,
		#app-mount .keybindGroup-JQs9x_:before{
			background-color: var(--secondary1-colour)
		}

		#app-mount .select-2TCrqx > [class*="css-"][class*="-container"] > [class*="css-"][class*="-menu"],
		#app-mount .css-2yldzf-control {
			background-color: var(--secondary1-colour);
			border-color: var(--secondary1-colour);
		}

		#app-mount a[target="_blank"] {color: var(--primary1-colour);}

		#app-mount .foreground-2aE44H {stroke: var(--primary1-colour);}

		#app-mount .previewOverlay-2O7_KC, #app-mount .formNotice-2_hHWR {background-color: var(--secondary1-colour)}
		#app-mount .media-engine-video {background: transparent;}

		#app-mount .wrapper-3jrx9n {border-color: var(--primary1-colour);}
		#app-mount .disabledSelected-2Kf0yZ {border-color: var(--secondary1-colour);}
		#app-mount .selected-mKYnfr.option-n0icdO {background-color: var(--primary1-colour);}
		#app-mount .option-n0icdO {background-color: var(--secondary2-colour)}

		#app-mount .focused-1mmYsC,
		#app-mount .inputDefault-_djjkz:focus {
			border-color: var(--primary1-colour);
		}

		#app-mount .questionMark-CWEQZn {
			margin-bottom: 3px;
			background-color: var(--primary1-colour);
		}
	 	
		#app-mount .connection-1fbD7X, 
		#app-mount .accountList-33MS45 {
			background-color: var(--secondary3-colour);
		}

		#app-mount .connectionHeader-2MDqhu {background-color: var(--secondary1-colour);}

	 	/*Server Settings*/
		#app-mount .emojiRow-zIc7ZX:before, 
		#app-mount .member-1q7VfX:before, 
		#app-mount .inviteSettingsInviteRow-3p2O-N:before, 
		#app-mount .bannedUser-1IalTM:before {
			background-color: var(--secondary1-colour)
		}


		#app-mount .deny-3nAuT6:not(.selected-2YhbGh) {background-color: rgba(100,0,0,0.5);}
		#app-mount .allow-1PzSY3:not(.selected-2YhbGh) {background-color: rgba(0,100,0,0.5);}

		#app-mount .passthrough-1c2ewQ {background-color: rgba(100,100,100,0.5)}
		#app-mount .passthrough-1c2ewQ.selected-2YhbGh {background-color: rgb(100,100,100)}

		/*CustomCSS*/
		#app-mount .ace_editor {background-color: var(--secondary3-colour);} /*Transparency*/
		#app-mount .ace_gutter, #app-mount #bd-customcss-attach-controls {background-color: var(--secondary3-colour)}/*Transparency*/

		#app-mount .ace_active-line {background-color: var(--primary3-colour)}
		#app-mount .ace_gutter-active-line {background-color: var(--primary3-colour)}

		#app-mount #bd-customcss-attach-controls {padding-left: 9px}

		#app-mount #bd-customcss-detach-controls-button button {transition: 0.1s background-color ease-in-out; background-color: var(--secondary1-colour);}
		#app-mount #bd-customcss-detach-controls-button button:hover {background-color: var(--primary3-colour)}
		#app-mount #bd-customcss-detach-controls-button button:active {background-color: var(--primary1-colour)}

		#app-mount #bd-customcss-detach-container {background-color: var(--secondary3-colour)} /*Transparency*/
		#app-mount #editor-detached button {background-color: var(--primary1-colour)}

		#app-mount .inline {background-color: var(--secondary1-colour)!important;}

		/*ChangeLog And Other Popups*/
		#app-mount .modal-yWgWj-, 
		#app-mount .bd-modal-inner, 
		#app-mount .messagesPopoutWrap-1MQ1bW, 
		#app-mount .messageGroupWrapper-o-Zw7G, 
		#app-mount .container-3ayLPN, 
		#app-mount .searchResultsWrap-2DKFzt,

		#app-mount .react-datepicker, 
		#app-mount .popoutList-T9CKZQ, 
		#app-mount .bd-modal-body, 
		#app-mount .root-1gCeng,
		#app-mount .noiseCancellationPopout-iRK2A0,
		#app-mount .colorPickerCustom-2CWBn2,

		#app-mount .keyboardShortcutsModal-3piNz7,
		#app-mount .bd-card {
			background-color: var(--secondary1-colour); 
			border-radius: 10px;
		}

		#app-mount .footer-3rDWdC,
		#app-mount .footer-3mqk7D,
		#app-mount .footer-2gL1pp {
			background-color: var(--secondary3-colour); 
			border-radius: 0 0 10px 10px;
		}
		#app-mount .header-1R_AjF, 
		#app-mount .react-datepicker__header {
			background-color: transparent;
		}

	/*User Popup*/
	#app-mount .bodyInner-245q0L {background-color: var(--secondary1-colour)}
	#app-mount .userPopout-xaxa6l {border-radius: 10px; background-color: var(--secondary1-colour);}
	#app-mount .bodyInnerWrapper-26fQXj { background-color: transparent }
	#app-mount .footer-3UKYOU {background-color: var(--secondary3-colour); padding: 16px;}
	#app-mount .footer-3UKYOU .inputDefault-_djjkz {background-color: var(--secondary1-colour);}

	#app-mount .topSection-y3p-_D,
	#app-mount .body-r6_QPy {
		background-color: var(--secondary3-colour);
	}
	
	#app-mount .activityName-1IaRLn {color: var(--activetext-colour)!important;}
		
	/*Upload Popup*/
	#app-mount .uploadModal-2ifh8j, #app-mount .bgScale-1otPtc {background-color: var(--secondary1-colour)}

	#app-mount .inner-3nWsbo {border-color: transparent;}

	#app-mount .uploadModal-2ifh8j .footer-3mqk7D button {height: 39px; background-color: var(--secondary2-colour)}
	#app-mount button.lookFilled-1Gx00P[type=submit] {color: var(--activetext-colour); margin-left: 8px}
	#app-mount .scrollableContainer-2NUZem {background-color: var(--secondary1-colour)}

	#app-mount .instructions-2Du9gG pre {background-color: transparent;}
	#app-mount .uploadDropModal-2kTwbc.error-kKl9o2 {background-color: rgba(240, 71, 71,0.5);}

	/*Search Popup*/
	#app-mount .searchHeader-1l-wpR, 
	#app-mount .header-ykumBX {
		background-color: var(--secondary1-colour); 
		border-radius: 10px 10px 0 0;
	}

	#app-mount .channelName-1QajIf {background-color: transparent;}

	#app-mount .hit-NLlWXA {background-color: var(--secondary2-colour); border-radius: 10px;}
	#app-mount .searchResult-3pzFAB.expanded-v2Szsz {background-color: var(--secondary1-colour); border-radius: 10px;}

	#app-mount .searchResult-3pzFAB {border: 2px solid var(--secondary1-colour); border-radius: 10px; background-color: var(--secondary1-colour)}
	#app-mount .searchResult-3pzFAB:before {border-radius: 10px;}
	#app-mount .option-96V44q:after {background-image: none;}

	#app-mount .react-datepicker__day:hover {background-color: var(--primary1-colour)}
	#app-mount .react-datepicker__day--selected::after {background-color: var(--primary1-colour)}
	#app-mount .hintValue-29ny8Z {background-color: var(--primary1-colour)}
	#app-mount .react-datepicker__day--disabled, 
	#app-mount .react-datepicker__day--outside-month {
		background-color: var(--secondary3-colour)
	}
	#app-mount .react-datepicker__day--disabled:hover, 
	#app-mount .react-datepicker__day--outside-month:hover {
		background-color: var(--primary2-colour)
	}

	/*Join & Create Server Popup*/
	#app-mount .action-1lSjCi {border-radius: 10px; background-color: var(--secondary1-colour)}

	#app-mount .header-3ZP1MY {color: var(--activetext-colour);} 
	#app-mount .create-3jownz .colorStandard-2KCXvj {color: rgb(114, 137, 218);}
	#app-mount .join-33Tr-7 .colorStandard-2KCXvj {color: #43b581;}

	#app-mount .inputWrapper-51e5iN input:focus {border-color: #43b581;}
	#app-mount .sampleLink-KPFu3I {color: #43b581;}

	#app-mount input[placeholder="Enter a server name"]:focus {border-color: rgb(114, 137, 218);}
	#app-mount a[href="//discordapp.com/guidelines"] {color: rgb(114, 137, 218);}

		/*Emoji Picker Popup*/
		#app-mount .header-1nkwgG {background-color: var(--secondary3-colour); border-top:1px solid var(--secondary2-colour);}
		#app-mount .searchBar-2pWH0_ {background-color: var(--secondary1-colour)!important}

		#app-mount .header-1nkwgG .input-1Rv96N {color: var(--activetext-colour);}
		#app-mount .header-1nkwgG ::-webkit-input-placeholder {color: var(--activetext-colour);}

		#app-mount .infoBar-U6oBFk {background-color: var(--secondary3-colour);}
		#app-mount .categories-1feg4n .selected-39BZ4S {border-color: var(--primary1-colour)}
		#app-mount .emojiPicker-3m1S-j ::-webkit-scrollbar-track {background-color: transparent;}

		#app-mount #bda-qem button {color: var(--activetext-colour); box-shadow: 0 0 0 0; border: 0;}
		#app-mount #bda-qem button:hover {background-color: var(--secondary2-colour);}
		#app-mount #bda-qem button.active {background-color: var(--secondary2-colour);}

		#app-mount #bda-qem-twitch-container,
		#app-mount #bda-qem-favourite-container {
			background-color: var(--secondary3-colour); 
			border-top: 1px solid var(--secondary2-colour);
		}

		#app-mount .emojiPicker-3m1S-j, 
		#app-mount #bda-qem, 
		#app-mount #bda-qem-twitch, 
		#app-mount #bda-qem-favourite, 
		#app-mount #bda-qem-emojis {
			background-color: var(--secondary3-colour); 
			border: 0!important;
		}

		/*BBD ContentErrors and Other BBD Modals*/
		#app-mount .error-link {color: var(--primary1-colour);}
		#app-mount .bd-modal-inner button {background-color: var(--primary1-colour)}

	/*TopBar*/
	#app-mount .typeWindows-2-g3UY {
		background-color: var(--secondary3-colour); 
		border-bottom: 2px solid var(--primary3-colour); 
		height: 30px;
		margin: 0px;
	}
	#app-mount .typeWindows-2-g3UY:after {
		content: "GGO Kirito v1.2.4 By VaporousCreeper";
		color: rgb(255,255,255,0.5);
		font-weight: 500;

		position: absolute;
		top: 8px;
		left: 43.2%;
	}

	#app-mount .wordmark-2u86JB {top: 3.3px;}
	#app-mount .winButton-3UMjdg {top: 1px;}

	/*Main Login*/
	#app-mount .splashBackground-1FRCko .image-2jyRAK, 
	#app-mount .splashBackground-1FRCko canvas {
		display: none;
	}
	#app-mount .splashBackground-1FRCko {background-image: none;}

	#app-mount .authBox-hW6HRx {background-color: var(--secondary1-colour); border-radius: 10px;}
	#app-mount .authBox-hW6HRx .linkButton-wzh5kV {color: var(--primary1-colour);}
	#app-mount .authBox-hW6HRx .inputDefault-_djjkz:focus {border-color: var(--primary1-colour);}

	#app-mount .leftSplit-1qOwnR {width: 80%;}

