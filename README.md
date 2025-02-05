<!DOCTYPE html>
<html lang="fa">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>فرم بریف طراحی بنر</title>
</head>
<body>
    <h2>فرم بریف طراحی بنر تبلیغاتی</h2>
    <form>
        <label>نام برند / شرکت:</label><br>
        <input type="text" name="brand_name" required><br><br>

        <label>زمینه فعالیت:</label><br>
        <input type="text" name="industry" required><br><br>

        <label>وب‌سایت یا شبکه‌های اجتماعی:</label><br>
        <input type="text" name="website"><br><br>

        <label>هدف از طراحی بنر:</label><br>
        <select name="goal">
            <option value="product_promotion">تبلیغ محصول</option>
            <option value="brand_awareness">افزایش آگاهی از برند</option>
            <option value="customer_attraction">جذب مشتری جدید</option>
            <option value="other">سایر (لطفاً توضیح دهید)</option>
        </select><br><br>

        <label>مخاطبان هدف:</label><br>
        <input type="text" name="target_audience"><br><br>

        <label>پیام اصلی بنر:</label><br>
        <textarea name="message" required></textarea><br><br>

        <label>رنگ‌های برند (در صورت مشخص بودن کدهای رنگی):</label><br>
        <input type="text" name="brand_colors"><br><br>

        <label>فرمت فایل خروجی:</label><br>
        <select name="file_format">
            <option value="JPEG">JPEG</option>
            <option value="PNG">PNG</option>
            <option value="GIF">GIF</option>
            <option value="PSD">PSD</option>
        </select><br><br>

        <label>مهلت تحویل طراحی:</label><br>
        <input type="date" name="deadline"><br><br>

        <label>بودجه موردنظر:</label><br>
        <input type="text" name="budget"><br><br>

        <input type="submit" value="ارسال">
    </form>
</body>
</html>
