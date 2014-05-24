Dwoo template engine for Codeigniter
============

Usage:

	$this->load->spark('dwootemplate/1.0.0');
	$this->dwootemplate->assign('itshowlate', date('H:i:s'));
	$this->dwootemplate->display('dwoowelcome.tpl');

Extra function:

Now you can set the template folder.
	$this->dwootemplate->set_view_folder('to/my/views');
The path is relative to APPATH