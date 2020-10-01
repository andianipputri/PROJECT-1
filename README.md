# PROJECT-1
PROJECT 1
<?php namespace App\Controllers;

class Page extends BaseController
{
	public function about()
	{
		echo view("about");
	}
    
    public function contact()
	{
		echo view("contact");
	}
    
    public function faqs()
	{
		echo view("faqs");
    }
}
