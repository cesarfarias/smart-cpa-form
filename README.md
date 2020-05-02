# Smart CPA Form

1. Copy the file `smart-cpa-form.php` to the lander folder.
2. Specify settings in the file `smart-cpa-form.php`
3. The lander file must have the extension .php !!!
4. In the lander file, add the code:
    
    4.1. inside <head>
        
        <?php require_once __DIR__ . '/smart-cpa-form.php'; ?>
        
    4.2. Where you want to see the form
    
        <div style="text-align:center"><?php echo $formHtml; ?></div>
        
    4.3. Before `</body>`
        
            <?php echo $formStyle; ?>
            <?php echo $formJs; ?>
