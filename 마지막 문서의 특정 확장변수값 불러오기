{@
$args->order_type = "asc";
$args->list_count = 1;
$oDocumentModel = &getModel('document');
$output = $oDocumentModel->getDocumentList($args);
}

<div loop="$output->data=>$key,$val">
	전일지급 : {$val->getExtraValue(5)}
</div>
