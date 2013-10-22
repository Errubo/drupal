<div id="page_wrapper"><!--start the page-->
      <!--start header-->
      <div id="header">
          <div id="head_link">
             <?php print render($page['head_link']); ?>
          </div>
         <div id="logo_main">
          <div id="logo-wrapper">
	    <div id="logo">
            <?php if ($logo): ?>
              <img src="<?php print $logo ?>" alt="<?php print $site_name_and_slogan ?>" title="<?php print $site_name_and_slogan ?>" id="logo" />
            <?php endif; ?>
	    </div>
	  </div>
          <div id="nav_menu">
            <?php if ($main_menu): ?>
          <div id="main-menu" class="navigation">
                <?php print theme('links__system_main_menu', array(
              'links' => $main_menu,
                 'attributes' => array(
                'id' => 'main-menu-links',
                  'class' => array('links', 'clearfix'),
                   ),
          'heading' => array(
            'level' => 'h2',
            'class' => array('element-invisible'),
          ),
        )); ?>
      </div> <!-- /#main-menu -->
      <?php endif; ?>
       </div>
    </div>
      </div>
      <!--end the header-->
      <div id="main-content">
            <?php print render($page['main_content']); ?>
      </div>
      <div id="footer">
            <?php print render($page['footer']); ?>
      </div> 
</div>
