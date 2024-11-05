# Create Administrative Report
## Các lớp phân tích:
### Boudary class
- ReportGenerationInterface: Giao diện cho quản trị viên để tạo báo cáo hành chính.
### Entities class
- AdministrativeReport: Đại diện cho báo cáo hành chính.
### Controller class
- ReportController: Điều khiển quá trình tạo báo cáo.
  # Biểu đồ Sequence của Create Administrative Repor
![Diagram](https://www.planttext.com/api/plantuml/png/V5D1RiCW4Bpp2exEmH_meKgLLbMkIJv0pJP5mk30sfLLvMKzz4dzGi76oCQqFd3OsPqPnilFr_VU8ZFODPAGMZ9hwGbQRV1W188HZ7uIwhwIch5y6Lgew1cDKDS0ZFDF35tTdw4AYczhJIlr073aAmfAhu2dI5_ijkXvrl1WP1oXvqae0qIr1UDzlkKZRuGI5Wr3qSEadjmriLbI52ZJszTQ8IXCgmOShrP91DwN0YS9Xsciu0pPsC2SnruBdYQoSX-nYtUI0sRU7BJm5DEwh__wosJFTHqTZtbZDOHGg0lbre4DjegrNIviAzaGi2c-AflnF9S8Uzz6ImacweqPXgcY3kjO9Ukvowi4Yfv9mNtQeVi_cbUj9J3bZVsTHLa-R0rNRWcQfbEYTbAMVWXy9vkcnUJyiYhQMR3vrknwLY4JIyZUlI_tPdy1003__mC0)
  # Login
### Boudary class
- LoginForm: Giao diện người dùng cho việc đăng nhập.
### Entities class
- User: Đại diện cho người dùng hệ thống (có thể là nhân viên hoặc quản trị viên).
### Controller class
- LoginController: Điều khiển quá trình đăng nhập.
  # Biểu đồ Sequence của Login
![Diagram](https://www.planttext.com/api/plantuml/png/R99DQiCm48NtEiKiKwWle4K9z0S2RIajFS3K4ev0Fs56JYWX9yiYH-eLAgjE8jdLJk-DvdqQwUTuMd94YhspGhGMcU6JDS5UG5eDz6cpKX8-8XdVZU8cbUq2JMKALbSIGATZRhTIYvkvzJRs-SzxJyqA_N2cUmwTyK-1t0KHbJD-nZY0otoNiQVsKLE6UKMNMs-3KQLPuXJU5grH6FNVHHxAgg-GAD6FXShmnkBt8r6W5ysCtJMcvhyFFgPfsScWArxiupfXcVOSlQZVudRs30LGYijde6dkYf798OR5LRZO1P64DZZN-vpCi3DnBQOrmxaS82jE5cAflKgVwHS00F__0m00)
  # Maintain Employee Information
  ### Boudary class
 - EmployeeManagementInterface: Giao diện cho quản trị viên để quản lý thông tin nhân viên.
  ### Entities class 
 - Employee: Đại diện cho thông tin nhân viên
   ### Controller class
 - EmployeeController: Điều khiển các hoạt động quản lý nhân viên.
   
   ![Diagram](https://www.planttext.com/api/plantuml/png/p9DDJiCm48NtFeMNOP4BP86AsYowAAe45nZiQR3adyYU52B4oLXm9Aw0JPCIN0kn99j8CzyRltbEFjxULu70qs0qOq932BmrlNOZ8dzXF3urnwcmbGs_8wziDpKi6CnA8AN74B9g3wD1I-iqNnsK05BEPWp1ymRb85Bhfvxp3gazcwYkBhktqKcfVdEoKshjIvvAuFtIs09upGFRWOKEqz2j9VG747E6FEKoOzMSPtDMng57f-J43hq4mZ_Z4ZKMyE_Rod0LUWrZwxtpkvXDj5oPqpiNN6ouTfQyqnhzFrpi25ejvs-0e7p6WtCQmQRzVhkxkhukRTvmuOmPRFfaCF0dHO-iW2tLKME-3WYChT3A-BTz0W00__y30000)
   # Run Payroll
   ### Boudary class
 - PayrollProcessingInterface: Giao diện cho quản trị viên để chạy quy trình trả lương.
   ### Entities class
- Payroll: Đại diện cho thông tin lương của nhân viên.
   ### Controller class
- PayrollController: Điều khiển quá trình chạy quy trình trả lương
# Biểu đồ Sequence của Run Payroll
![Diagram](https://www.planttext.com/api/plantuml/png/b5DBJiCm4Dtd5BDC9Ne12rKLRIMG05NgWhLnXiQgFv5d0efGJyQ28t45d3OEQSYcMJZol9dtdiVZdw_l9R4CN5kJPSf88jZA9dXZu3E3-CsXEk_Nab50ktPnj9Nn3I89UDJ4jvjklpZX0A5s7LK-4_3kTT41IXfLcqWKuJon24ZrCRdmzQl1x9Wi9QZtbAeU2W4x3jhjEy19YwDGz6_HyHDowSVffQy3lVXmmA9NFICaZGpDHH1WZxpfbTjJ3SXEw7EKduflXnwc4kx_ZEIp_wgxavjyeZLtqXrs3J7QhZa0LV0AYTOweE8rLfuqJ_Jv1gJrjUF4UNb9LVJ7gnBLuOhIusY6Ljvn-yVGczDEipxV_SHeEC_whKaob0-8qrZEvui9UW5MEhb7kiZhvqQafemI1jqJqHfZa8e9FZINMRP4LyHtyGi00F__0m00)
