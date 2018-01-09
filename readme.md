# CUSC-HRM-WebApp

## Work Parts
1. Đăng nhập/Đăng xuất
2. Phân quyền theo vai trò
3. Đánh giá xếp loại nhân viên
4. Thêm/Sửa/Xóa (CRUD)
5. Báo cáo theo yêu cầu
6. Xuất báo cáo PDF/Excel
7. Quản lý lý lịch nhân viên
8. Tìm kiếm nhân viên
9. Hiển thị thông tin nhân viên
10. Song ngữ Việt - Anh
* Dang: 1 - 2 - 3 - 6 - 10
* Thuc: CSDL + 4 - 5 - 7 - 8 - 9

## Database
### 1. LoaiBangCap
* 1.1 MaLoaiBangCap
* 1.2 TenLoaiBangCap
* 1.3 MoTaBangCap
### 2. BangCap (theo NV)
* 2.1 TenBangCap
* 2.2 LoaiBangCap
* 2.3 NgayCap
* 2.4 DonViCapPhat
* 2.5 MaSoBangCap
### 3. LoaiKhenThuong
* 3.1 MaLoaiKhenThuong
* 3.2 TenLoaiKhenThuong
* 3.3 MoTaKhenThuong
### 4. KhenThuong (theo NV)
* 4.1 MaKhenThuong
* 4.2 MaSoNV
* 4.3 TenKhenThuong
* 4.4 LyDoKhenThuong
* 4.5 NgayKhenThuong
### 5. LoaiKyLuat
* 5.1 MaLoaiKyLuat
* 5.2 TenLoaiKyLuat
* 5.3 MoTaKyLuat
### 6. KyLuat (theo NV)
* 6.1 MaKyLuat
* 6.2 MaSoNV
* 6.3 TenKyLuat
* 6.4 LyDoKyLuat
* 6.5 NgayKyLuat
### 7. LuongCoBan
* 7.1 MaLuong
* 7.2 LuongCoBan
* 7.3 NgayApDung
### 8. HeSoLuong
* 8.1 MaHeSo
* 8.2 HeSoLuong
### 9. SoYeuLyLich
* 9.1 TenKhac
* 9.2 NgayThangNamSinh
* 9.3 QueQuan
* 9.4 DiaChiHienTai
* 9.5 NhomMau
* 9.6 MaSoBHXH
* 9.7 MaSoDinhDanhCaNhan (CMND/CCCD/HoChieu - kem ngay cap/noi cap)
* 9.8 TinhTrangHonNhan
* 9.9 GioiTinh
* 9.10 SoDienThoai
* 9.11 Email
* 9.12 TaiKhoanNganHang
### 10. NhanVien
* 10.1 MaSoNV
* 10.2 HoTen
* 10.3 SoHopDong
* 10.4 ChucVu
* 10.5 BangCap (cao nhat)
### 11. TaiKhoan
* 11.1 TaiKhoan_master
* 11.2 TaiKhoan_chucvu
### 12. ChamCong
* 12.1 MaSoNV
* 12.2 TenCaLamViec (Ca-sang/Ca-chieu/Ca-toi)
* 12.3 VaoCa (time)
* 12.4 TanCa (time)
* 12.5 NgayChamCong
### 13. NhomQuyen
* 13.1 MaNhomQuyen
* 13.2 NhomQuyen_BanGiamDoc-PhongBan-Nhanvien
* 13.3 MaChucVu (default master)
* 13.4 MaQuyen
* 13.5 MoTaNhomQuyen
### 14. ChucVu
* 14.1 MaChucVu
* 14.2 TenChucVu
* 14.3 MoTaChucVu
* 14.4 CapTruong-CapPho
### 15. VaiTroCuaQuyen
* 15.1 MaQuyen
* 15.2 VaiTro
### 15. DanhGiaXepLoai (theo NV)
* 15.1 MaSoNV
* 15.2 XepLoai
* 15.3 DanhGia (tuy-chon)
* 15.4 ThoiGianDanhGia
### 16. LichSuCongTac (theo NV)
* 16.1 NgayVaoLam
* 16.2 DonViCongTac
* 16.3 ChucVu
* 16.4 CongViec
* 16.5 VanBanMinhChung
### 17. PhapChe
* 17.1 MaVanBanQuyetDinh
* 17.2 TenVanBan
* 17.3 TomTatVanBan
* 17.4 NgayKy
* 17.5 HinhAnh
### 18. LichSuNangBacLuong (theo NV)
* 18.1 SoQuyetDinh
* 18.2 NoiDungQuyetDinh (tom-tat)
* 18.3 BacLuongHienTai
* 18.4 BacLuongMoi
* 18.5 ThoiGian
### 19. DonViCongTac (Hoi so - Chi nhanh)
* 19.1 MaDonVi
* 19.2 TenDonVi
* 19.3 TinhThanhPho
* 19.4 QuanHuyenThixa
### 20. LichSuXuatBaoCao
* 20.1 TenBaoCao
* 20.2 LoaiBaoCao
* 20.3 ThoiGianXuat
* 20.4 TinhTrang
### 21. TroCapPhuCap
* 21.1 MaTroCap
* 21.2 TroCap
* 21.3 NgayApDung
### 22. BangLuong (theoNV)
* 22.1 MaSoBangLuong
* 22.2 MaSoNV
* 22.3 ThangThuong
* 22.4 NgayCong
* 22.5 PhuCapTroCap
* 22.6 LuongCoBan
* 22.7 LuongThuong
* 22.8 LuongTru
* 22.9 Thue
* 22.10 PhiBHXH
* 22.11 NoLuong
* 22.12 NgayXuatBangLuong
### 23. BaoHiemXaHoi
* 23.1 MaSoBHXH
* 23.2 TenNguoiThuHuong
* 23.3 PhiBHXH
* 23.4 NgayCap
* 23.5 NgayHetHan
* 23.6 DonViCap

## My Team
- Le Nguyen Thuc D17316
- Nguyen Van Dang D17319

## Thank for working
