# HumHub Template Theme
This is just a template for a HumHub theme.

### Setup/Install (Windows PC/Desktop User)
- [Download](https://github.com/GreenMeteor/humhub-template-theme/archive/master.zip) or `git@github.com:GreenMeteor/humhub-template-theme.git`
- Install [Nodejs](https://nodejs.org/en/download/)
- Install LESS `npm install less -g`
- To change colors (basic themeing) edit your `/themes/Template/less/variables.less`
- Open your Command Terminal and use the following `cd /path/to/HumHub/themes/Template/less`
- Run `lessc build.less css/theme.css`
- Upload via FTP/SFTP or if you have a File Manager (CPanel users should have one regardless) to `/{HUMHUB-INSTANCE}/themes`.

> Note: You should do as [HumHub's Docs](https://docs.humhub.org/docs/theme/overview) suggests for if you wish to do this from your server and not your PC/Desktop.
