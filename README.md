$user_info = get_userdata(1);
$registered_date = $user_info->user_registered;
echo "تاریخ ثبت نام: " . date("d-m-Y", strtotime($registered_date));
