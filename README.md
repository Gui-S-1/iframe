# iframe
iframe test
/* cyrillic-ext */
@font-face {
  font-family: 'Roboto';
  font-style: italic;
  font-weight: 500;
  font-display: swap;
  src: url(https://fonts.gstatic.com/s/roboto/v20/KFOjCnqEu92Fr1Mu51S7ACc3CsTKlA.woff2) format('woff2');
  unicode-range: U+0460-052F, U+1C80-1C88, U+20B4, U+2DE0-2DFF, U+A640-A69F, U+FE2E-FE2F;
}
/* cyrillic */
@font-face {
  font-family: 'Roboto';
  font-style: italic;
  font-weight: 500;
  font-display: swap;
  src: url(https://fonts.gstatic.com/s/roboto/v20/KFOjCnqEu92Fr1Mu51S7ACc-CsTKlA.woff2) format('woff2');
  unicode-range: U+0400-045F, U+0490-0491, U+04B0-04B1, U+2116;
}
/* greek-ext */
@font-face {
  font-family: 'Roboto';
  font-style: italic;
  font-weight: 500;
  font-display: swap;
  src: url(https://fonts.gstatic.com/s/roboto/v20/KFOjCnqEu92Fr1Mu51S7ACc2CsTKlA.woff2) format('woff2');
  unicode-range: U+1F00-1FFF;
}
/* greek */
@font-face {
  font-family: 'Roboto';
  font-style: italic;
  font-weight: 500;
  font-display: swap;
  src: url(https://fonts.gstatic.com/s/roboto/v20/KFOjCnqEu92Fr1Mu51S7ACc5CsTKlA.woff2) format('woff2');
  unicode-range: U+0370-03FF;
}
/* vietnamese */
@font-face {
  font-family: 'Roboto';
  font-style: italic;
  font-weight: 500;
  font-display: swap;
  src: url(https://fonts.gstatic.com/s/roboto/v20/KFOjCnqEu92Fr1Mu51S7ACc1CsTKlA.woff2) format('woff2');
  unicode-range: U+0102-0103, U+0110-0111, U+0128-0129, U+0168-0169, U+01A0-01A1, U+01AF-01B0, U+1EA0-1EF9, U+20AB;
}
/* latin-ext */
@font-face {
  font-family: 'Roboto';
  font-style: italic;
  font-weight: 500;
  font-display: swap;
  src: url(https://fonts.gstatic.com/s/roboto/v20/KFOjCnqEu92Fr1Mu51S7ACc0CsTKlA.woff2) format('woff2');
  unicode-range: U+0100-024F, U+0259, U+1E00-1EFF, U+2020, U+20A0-20AB, U+20AD-20CF, U+2113, U+2C60-2C7F, U+A720-A7FF;
}
/* latin */
@font-face {
  font-family: 'Roboto';
  font-style: italic;
  font-weight: 500;
  font-display: swap;
  src: url(https://fonts.gstatic.com/s/roboto/v20/KFOjCnqEu92Fr1Mu51S7ACc6CsQ.woff2) format('woff2');
  unicode-range: U+0000-00FF, U+0131, U+0152-0153, U+02BB-02BC, U+02C6, U+02DA, U+02DC, U+2000-206F, U+2074, U+20AC, U+2122, U+2191, U+2193, U+2212, U+2215, U+FEFF, U+FFFD;
}

@font-face {font-family: "SFProDisplay-Regular";
    src: url("../../assets/font/SFProDisplay-Regular.eot"); /* IE9*/
    src: url("../../assets/font/SFProDisplay-Regular.eot?#iefix") format("embedded-opentype"), /* IE6-IE8 */
    url("../../assets/font/SFProDisplay-Regular.woff2") format("woff2"), /* chrome firefox */
    url("../../assets/font/SFProDisplay-Regular.woff") format("woff"), /* chrome firefox */
    url("../../assets/font/SFProDisplay-Regular.ttf") format("truetype"), /* chrome firefox opera Safari, Android, iOS 4.2+*/
    url("../../assets/font/SFProDisplay-Regular.svg#SFProDisplay-Regular") format("svg"); /* iOS 4.1- */
}
@font-face {font-family: "SFProDisplay-Semibold";
    src: url("../../assets/font/SFProDisplay-Semibold.eot"); /* IE9*/
    src: url("../../assets/font/SFProDisplay-Semibold.eot?#iefix") format("embedded-opentype"), /* IE6-IE8 */
    url("../../assets/font/SFProDisplay-Semibold.woff2") format("woff2"), /* chrome firefox */
    url("../../assets/font/SFProDisplay-Semibold.woff") format("woff"), /* chrome firefox */
    url("../../assets/font/SFProDisplay-Semibold.ttf") format("truetype"), /* chrome firefox opera Safari, Android, iOS 4.2+*/
    url("../../assets/font/SFProDisplay-Semibold.svg#SFProDisplay-Semibold") format("svg"); /* iOS 4.1- */
}

.modal::-webkit-scrollbar {
    width: 8px!important;
}
.modal::-webkit-scrollbar-thumb {
    background: #888!important;
}
.modal::-webkit-scrollbar-track {
    background: #a7a7a7!important;
}
.modal {
    background: #eeeaea;
    text-align: center;
    width: 230px;
    height: 270px;
    z-index: 999999999;
    position: absolute;
    top: 0;
    left: 0;
    bottom: 0;
    right: 0;
    border-radius: 3px;
    margin: auto;
    padding: 20px;
    -webkit-filter: url(#blur);
    filter: url(#blur);
    -webkit-transform: translate3d(0, -900%, 0);
    transform: translate3d(0, -900%, 0);
}
.close-modal {
	background: none;
    border: none;
    position: absolute;
    font-size: 20px;
    cursor: pointer;
    right: 10px;
    top: 10px;
    color: #334;
    outline: none;
}
.download-item {
	display: table;
    vertical-align: middle;
    height: 55px;
    width: 100%;
}
.partdditem {
    display: table-cell;
    vertical-align: middle;
    margin: 6%;
}
.not-copyable {
	-webkit-touch-callout: none;
	-webkit-user-select: none;
	-khtml-user-select: none;
	-moz-user-select: none;
	-ms-user-select: none;
	user-select: none;
}
.hdlabel {
    font-family: 'Roboto', sans-serif;
    font-size: 10px;
    width: 4%;
    text-align: right;
    padding-right: 2px;
}
.size {
    font-family: SFProDisplay-Regular;
    font-size: 15px;
    text-align: left;
    opacity: .5;
    width: 14%;
}
.quality {
    font-family: SFProDisplay-Semibold;
    font-size: 15px;
    width: 13%;
    text-align: left;
}
.down-icon {
	transition: background-size 2s ease-in;
	-moz-transition: background-size 2s ease-in;
	-ms-transition: background-size 2s ease-in;
	-o-transition: background-size 2s ease-in;
	-webkit-transition: background-size 2s ease-in;
	background-image: url(https://fonts.gstatic.com/s/i/materialicons/get_app/v5/24px.svg?download=true);
	cursor: pointer;
    width: 12%;
    background-position: center;
    background-repeat: no-repeat;
}
.down-icon:hover {
	background-size: 50%;
}

