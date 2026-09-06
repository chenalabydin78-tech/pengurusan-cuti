SISTEM PENGURUSAN CUTI BAHAGIAN PENILAIAN & PENCUKAIAN (VAL)
Dewan Bandaraya Kuching Utara (DBKU)
Effective Date: Januari 2026
📦 DELIVERABLES (3 FILES)
1. Sistem_Pengurusan_Cuti_DBKU_Bahagian_Penilaian_2026.xlsx
File Utama - Main System Workbook
Ini adalah workbook utama yang mengandungi semua fungsi sistem. Terdiri daripada 9 sheets:
SHEETS DALAM WORKBOOK (TOTAL: 15 SHEETS):
LEAVE MANAGEMENT (9 sheets):
Sheet
Fungsi
User
ADMIN
Staff Master Database - Data kakitangan (nama, gaji, cuti entitlement, unit, penyelia)
Jenny, Zainal
GCR_MASTER
GCR Tracker - Track accumulated GCR, redeemed, balance, & payment calculation
Jenny, Finance
LEAVE_REQUEST
Leave Application Form - Submit requests, track approval chain, status
All Staff
LEAVE_BALANCE
Real-time Balance Tracker - Annual, GCR, Sick Leave balance per staff
All Staff
MONTHLY_CALENDAR
Jadual Bulanan - Auto-generated calendar with color-coding by leave type
Supervisors, Management
HEADCOUNT
Daily Staffing Dashboard - In-office count per day, by counter location
Management, Planners
MONTHLY_REPORT
Printable Summary - Monthly leave report (DBKU branded, WhatsApp-ready)
Management
CARRYOVER_2027
End of Year Calculation - Carryover balance untuk tahun baru
Zainal, Finance
APPROVAL_LOG
Audit Trail - History semua requests dan approvals
Zainal
TRAINING MANAGEMENT (6 sheets - NEW):
Sheet
Fungsi
User
TRAINING_SCHEDULE
Input training schedule dari HRM (date, name, time, type, category) - Auto-generate ID
HRM, Admin
TRAINING_NOMINATIONS
Nominate staff untuk training, check leave conflict
Supervisors
TRAINING_ATTENDANCE
Input attendance data (staff, hours attended)
Jenny
TRAINING_HOURS_TRACKER
Real-time tracking (target 40 hrs per year, by training type)
All Staff
TRAINING_REPORTS
Printable summary (individual progress, at-risk staff, by type)
All Stakeholders
TRAINING_LEAVE_CONFLICT
Log semua leave-training conflicts & resolutions
Zainal
KEY FORMULAS:
Annual Leave Balance = Entitlement + Carryover - Diambil - Dijual
GCR Balance = MIN(Accumulated - Redeemed, 180)
Max Boleh Redeem = MIN(15, GCR Balance)
GCR Payment = 1/30 × Gaji Bulanan × Hari Ditebus
Carryover ke Tahun Depan = Annual - Diambil - Dijual
FEATURES:
✅ Approval Workflow (Penyelia → Pegawai → Timbalan → Pengarah) ✅ Data Validation Dropdowns (Unit, Gred, Status, Jenis Cuti) ✅ Automatic Balance Calculation ✅ GCR Redemption Simulator (December only) ✅ Leave to be Sold Simulator (Max 15 hari atau 50% entitlement) ✅ Real-time Constraint Checking ✅ DBKU Professional Branding (Dark Green #1B5E20, Amber Notes, Calibri Font)
2. Template_Pengumpulan_Data_Cuti_Jenny.xlsx
Data Collection Template untuk Jenny - Untuk Input Data Historis
File terpisah untuk Jenny mengumpul data cuti Jan-Sept 2026. Terdiri daripada 4 sheets:
SHEETS:
Sheet
Fungsi
INSTRUCTIONS
Panduan lengkap cara mengisi template
GCR_INITIAL
Input GCR balances setiap staff (end 2025)
MONTHLY_TEMPLATE
Template reusable untuk input cuti bulanan
SUMMARY
Ringkasan data Jan-Sept 2026
CARA MENGGUNAKAN:
Buka file template
Baca sheet INSTRUCTIONS
Fill GCR_INITIAL dengan GCR balances per staff
Copy MONTHLY_TEMPLATE dan rename setiap bulan (Januari, Februari, dll)
Isi leave data setiap bulan menggunakan dropdown untuk Jenis Cuti
Update SUMMARY dengan total cuti per staff
Berikan file ke Zainal untuk processing ke main system
DATA YANG DIKUMPUL:
Nama staff & unit
Tarikh cuti (dari-hingga)
Jenis cuti (Tahunan, GCR, Sick, QO, Time Off, Kursus)
Bilangan hari
Catatan/Sebab
3. Panduan_Sistem_Pengurusan_Cuti_DBKU.docx
Comprehensive User Guide - Panduan Lengkap Penggunaan Sistem
Dokumen Word yang memberikan penjelasan detail tentang:
Pengenalan sistem & objectives
Struktur organisasi & approval chains
Jenis-jenis cuti & rules
Cara menggunakan sistem (step-by-step)
Constraints & business rules
Simulators & bayaran GCR
FAQ & troubleshooting
Document Format: DBKU Branded (Dark green headers, professional layout)
🚀 IMPLEMENTATION TIMELINE
FASE 1: DATA COLLECTION (JANUARY - SEPTEMBER 2026)
Owner: Jenny Peng (Unit Pentadbiran)
Langkah-langkah:
1. Terima template dari Zainal
2. Fill GCR_INITIAL dengan GCR balances setiap staff (end 2025)
3. Untuk setiap bulan (Jan-Sept):
   - Copy MONTHLY_TEMPLATE
   - Rename: Januari, Februari, Maret, dll
   - Input leave data staff per hari
4. Update SUMMARY sheet dengan total bulanan
5. Berikan file lengkap ke Zainal akhir September
FASE 2: SYSTEM SETUP (SEPTEMBER - OCTOBER 2026)
Owner: Zainal Abidin (Penyelia Unit RTG)
Langkah-langkah:
1. Terima file historis dari Jenny
2. Transfer data historis ke main system (ADMIN, GCR_MASTER, LEAVE_REQUEST sheets)
3. Verify balance calculations
4. Setup approval workflows
5. Train staff & supervisors
6. Go-live training session dengan semua users
FASE 3: REAL-TIME OPERATIONS (OCTOBER - DECEMBER 2026)
Owners: All Staff, Supervisors, Pengarah
Ongoing:
- Staff submit leave requests (LEAVE_REQUEST sheet)
- Supervisors approve/reject
- System track balances automatically
- Monthly reports generated
- End-of-year carryover calculation
FASE 4: YEAR-END CLOSURE (DECEMBER 2026)
Owner: Zainal Abidin
Langkah-langkah:
1. Run CARRYOVER_2027 sheet
2. Calculate baki cuti forward untuk setiap staff
3. Verify GCR balances (capped at 180)
4. Prepare year-end report
5. Export carryover data untuk bulk load 2027
FASE 5: TAHUN BARU (JANUARY 2027)
Owner: Zainal Abidin
Langkah-langkah:
1. Bulk load carryover balances dari 2026
2. Reset annual entitlements untuk 2027
3. Continue operational tracking
4. Monthly reports untuk 2027
🎓 TRAINING MANAGEMENT MODULE (NEW)
OVERVIEW:
Training management is integrated dengan leave system untuk prevent conflict. Key features:
✅ HRM/Admin submit training schedule
✅ Nominate staff untuk training
✅ Auto-block leave if training scheduled >= 5 hours
✅ Track hours towards 40-hour annual KPI
✅ Prevent double-booking (cuti + training same date)
6 NEW SHEETS ADDED:
Sheet
Owner
Fungsi
TRAINING_SCHEDULE
HRM/Admin
Input training schedule (date, name, time, type, category) - Auto-generate ID
TRAINING_NOMINATIONS
Supervisors
Nominate staff, check leave conflict, approve attendance
TRAINING_ATTENDANCE
Jenny
Input attendance data dari HRM (staff, hours attended)
TRAINING_HOURS_TRACKER
All
Real-time tracking per staff (target 40 hrs, by training type)
TRAINING_REPORTS
All
Printable summary (individual progress, at-risk staff, by type)
TRAINING_LEAVE_CONFLICT
Zainal
Log semua conflicts detected & resolutions
TRAINING RULES:
TRAINING DURATION RULES:
├─ < 5 HOURS: No leave record, staff attend + work normal hours
├─ >= 5 HOURS: 
│  ├─ Auto-create "Cuti Kursus/Latihan" record
│  ├─ BLOCK leave application (cannot override)
│  ├─ NOT deducted from Annual Leave Balance
│  └─ Count towards 40-hour KPI
│
MULTI-DAY TRAINING:
├─ 8 hours per day assumed
└─ Full duration blocked for all days

TRAINING ATTRIBUTES:
├─ Date, Name, Start Time, End Time (auto-calculate hours)
├─ Auto-generate Training ID (TRN-001, TRN-002, etc)
├─ Type: Workshop, Kursus, Lawatan, Seminar, Konvensyen, Exam
├─ Category: Internal, External
└─ Submitted by: HRM or Department Admin

40 HOURS KPI:
├─ Calendar Year: Jan-Dec
├─ Warning by June: If < 20 hours
├─ Alert by November: If < 40 hours
├─ NO carryover to next year
└─ Mandatory for all staff (measured as KPI)

LEAVE CONFLICT PREVENTION:
├─ Training >= 5 hrs scheduled → Cannot apply leave on those dates
├─ System completely BLOCKS (no override option)
├─ If training < 5 hrs → Staff normal work + attend training
├─ Multi-day → Blocks all training days
└─ Logged in TRAINING_LEAVE_CONFLICT sheet
WORKFLOW:
STEP 1: HRM Submit Training Schedule
├─ Open TRAINING_SCHEDULE sheet
├─ Input: Date, Training Name, Time, Duration, Type, Category
├─ System auto-generate Training ID (TRN-001, TRN-002, etc)
└─ Status: Scheduled

STEP 2: Nominate Staff
├─ Open TRAINING_NOMINATIONS sheet
├─ Input Training ID, Staff Name, Nominated By
├─ System auto-check: Is staff on leave? Duration >= 5 hrs?
├─ If >= 5 hrs → Flag "CHECK LEAVE BLOCK"
├─ If conflict exists → Warning to nominator
└─ Status: Nominated → Approved

STEP 3: Jenny Input Attendance
├─ Receive attendance list dari HRM/Trainer
├─ Open TRAINING_ATTENDANCE sheet
├─ Input: Training ID, Staff Name, Hours Attended
├─ System auto-update TRAINING_HOURS_TRACKER
└─ Auto-create "Cuti Kursus" record in LEAVE_REQUEST (if >= 5 hrs)

STEP 4: Track Progress
├─ Open TRAINING_HOURS_TRACKER
├─ Real-time view: Total hours, Target 40, Balance, Status
├─ By training type breakdown
├─ Alert if < target by milestone dates
└─ Generate TRAINING_REPORTS for stakeholders

STEP 5: Leave System Integration
├─ When staff tries to apply leave on training date:
│  └─ System checks TRAINING_SCHEDULE
│  └─ If training >= 5 hrs → BLOCK completely
│  └─ Show message: "Training [name] scheduled. Cannot apply leave."
└─ Auto-create "Cuti Kursus" record (not deducted from annual)
DATA OWNERSHIP:
HRM/Bahagian Pembangunan Sumber Manusia:
├─ Submit training schedule (via email → admin input)
├─ Provide attendance list after training
└─ Central training coordinator role

Department Administrator (VAL):
├─ Input training data from HRM
├─ Nominate staff untuk training
├─ Monitor leave conflicts
└─ Generate reports

Jenny Peng (Unit Pentadbiran):
├─ Input attendance data
├─ Update training hours
├─ Maintain data accuracy
└─ Report to supervisors

Supervisors (Zainal, Mohd Syazani, Jenny):
├─ Nominate staff
├─ Approve training attendance
├─ Monitor progress towards 40 hrs
└─ Alert staff at risk

All Staff:
├─ View their training hours balance
├─ Cannot apply leave if training >= 5 hrs scheduled
├─ Must achieve 40 hours per year
└─ See TRAINING_REPORTS for progress
REPORTING STAKEHOLDERS:
Can VIEW TRAINING_REPORTS:
✅ Jenny Peng (Unit Pentadbiran)
✅ Shafiza Jaya (Ketua Bahagian)
✅ Mohd Hafiz Suria (Pegawai Penilaian)
✅ Mohd Syazani (Penyelia Unit Penilaian)
✅ Zainal Abidin (Penyelia Unit RTG)
✅ HRM (Bahagian Pembangunan Sumber Manusia)
📋 ORGANIZATIONAL STRUCTURE & APPROVAL CHAINS
HIERARCHY:
Pengarah (Ramzi Abdillah)
├─ Timbalan Pengarah (FCS Abang Iskandar Bolhassan)
│  ├─ Pegawai Penilaian (Shafiza Jaya, Mohd Hafiz Suria)
│  ├─ HRM - Bahagian Pembangunan Sumber Manusia (Training Programs)
│  └─ Unit Supervisors:
│     ├─ Unit Rating (Zainal Abidin)
│     ├─ Unit Penilaian (Mohd Syazani)
│     └─ Unit Pentadbiran (Jenny Peng)
APPROVAL CHAINS:
PEGAWAI SKEL A:
Applicant → Penyelia Unit → Timbalan Pengarah → Pengarah Ramzi Abdillah

PEGAWAI SKEL B:
Applicant → Penyelia Unit → Pegawai Penilaian (Shafiza/Hafiz) → Timbalan Pengarah

PEGAWAI SKEL C:
Applicant → Penyelia Unit → Shafiza Jaya (Ketua Bahagian)

GCR REDEMPTION (December Only):
Applicant → Jenny Peng (Unit Pentadbiran) → Shafiza Jaya (luluskan)
🎯 KEY FEATURES & CONSTRAINTS
LEAVE TYPES:
Jenis
Max/Year
Balance
Carryover
Dikira dalam Annual
Cuti Tahunan
Varies
✓
✓ Unlimited
YES
GCR
15/tahun
✓ Capped 180
✓
NO
Cuti Sakit
12 hari
✓
✗
NO
QO
N/A
✓ Info only
✓
NO
Time Off
N/A
✓ Info only
✓
NO
Cuti Kursus
N/A
✓ Info only
✓
NO
BUSINESS RULES:
DEPOT Staffing: Hanya 1 orang per hari (Rotation: RWD, FO, DFF, MAG, AM, NAS, ZAN)
SATOK Coverage: JLL tetap - auto-assign replacement jika cuti
Maximum Cuti Sehari: Max 2-3 orang Unit Rating sehari (System warn jika exceed)
Sick Leave Alert: Alert jika > 10 hari per tahun
GCR Cap: Max 180 hari (auto-capped oleh system)
Cuti Dijual: Max 15 hari OR 50% dari annual entitlement (whichever is lower)
GCR Redemption: December only, sekali per tahun (max 15 hari)
GCR Payment Formula: 1/30 × Gaji Bulanan × Hari Ditebus
👥 USER ROLES & RESPONSIBILITIES
ZAINAL ABIDIN (Penyelia Unit RTG)
Leave Management:
Approve/reject leave requests dari staff RTG
Monitor DEPOT duty roster
Track leave balance per staff
Generate monthly reports
Manage carryover calculations
Overall system administration
Training Management:
Nominate staff untuk training programs
Monitor 40-hour training KPI for RTG staff
Track leave-training conflicts
Generate training reports
Alert staff at risk (< target hours)
JENNY PENG (Penyelia Unit Pentadbiran)
Leave Management:
Collect historical leave data (Jan-Sept 2026)
Input GCR initial balances
Maintain staff master data
Verify GCR calculations
Process GCR redemption approvals
Training Management:
Input training attendance data dari HRM
Update training hours untuk all staff
Maintain TRAINING_HOURS_TRACKER accuracy
Coordinate with HRM untuk training data
View training reports for all units
MOHD SYAZANI (Penyelia Unit Penilaian)
Leave Management:
Approve/reject leave requests Unit Penilaian
Monitor balance constraints
Training Management:
Nominate staff Unit Penilaian untuk training
Monitor training progress for own unit
SHAFIZA JAYA (Ketua Bahagian VAL / Pegawai Penilaian)
Leave Management:
Final approval untuk Pegawai Skel C
Approve GCR redemption requests
Review monthly reports
Strategic oversight
Training Management:
View training reports (strategic overview)
Monitor unit-level progress towards 40 hrs
Alert if units at risk
HRM (Bahagian Pembangunan Sumber Manusia)
Training Management:
Submit training schedule ke system (via admin input)
Provide attendance list after each training
Coordinate with VAL untuk nominations
Approve external training (depends on scope)
Central training coordinator
ALL STAFF
Leave Management:
Submit leave requests via LEAVE_REQUEST sheet
Check balance via LEAVE_BALANCE sheet
Use leave dijual & GCR simulators
Participate in approval process
Training Management:
View own training hours balance
Cannot apply leave if training >= 5 hrs scheduled (system blocks)
Must achieve 40 hours annually
View own progress in TRAINING_HOURS_TRACKER
🔧 SYSTEM MAINTENANCE & UPDATES
MONTHLY:
Generate MONTHLY_REPORT
Review constraint violations
Verify balance calculations
Export reports for WhatsApp/Email sharing
QUARTERLY:
Review cumulative balances
Check for sick leave warnings
Verify no staff exceed GCR 180 cap
Summary review meeting
ANNUALLY:
End-of-year carryover calculation
GCR balance verification
Prepare 2027 data
System reset & setup for new year
📞 SUPPORT & CONTACT
FOR TECHNICAL ISSUES:
Zainal Abidin (Penyelia Unit RTG)
Leave request approval
System troubleshooting
Balance calculations
Reports & exports
FOR GCR & COMPENSATION:
Jenny Peng (Unit Pentadbiran / Data Custodian)
GCR balance verification
Payment calculations
Staff data accuracy
FOR POLICY & APPROVALS:
Shafiza Jaya (Ketua Bahagian VAL)
Policy interpretation
Final approvals
Strategic decisions
✅ CHECKLIST BEFORE GO-LIVE
LEAVE MANAGEMENT:
Staff master data entered (ADMIN sheet)
GCR initial balances loaded (GCR_MASTER sheet)
Historical data (Jan-Sept 2026) entered (LEAVE_REQUEST sheet)
Approval chains configured
Data validation dropdowns tested
Formula calculations verified
Monthly template tested
Report exports working
TRAINING MANAGEMENT:
HRM provided training schedule format
TRAINING_SCHEDULE sheet setup with sample data
TRAINING_HOURS_TRACKER formulas verified
Leave-training conflict logic tested
Jenny trained on attendance input process
HRM contact person identified
Training ID generation confirmed (TRN-001, TRN-002, etc)
GENERAL:
All users trained on both modules
Backup copy created
Go-live announcement sent
Support contact info distributed
📄 REFERENCE DOCUMENTS
File Reference Format:
DBKU/VAL/RTG/SistemCuti/2026
DBKU/VAL/Recovery/SistemCuti/2026
Pekeliling/Circular References:
Pekeliling Cuti Dijual - Max 180 hari
Pekeliling GCR - Had maksimum 180 hari (effective 1 Jan 2023)
Garis Panduan Penebusan Awal GCR - Max 90 hari (50% dari 180)
🎓 TRAINING MATERIALS
All users should read:
Panduan_Sistem_Pengurusan_Cuti_DBKU.docx - Full user guide
INSTRUCTIONS sheet dalam Template_Pengumpulan_Data_Cuti_Jenny.xlsx
📝 NOTES & DISCLAIMERS
System uses Excel formulas for automatic calculation - ensure not to delete formula cells
Always use MONTHLY_TEMPLATE for consistent data format
GCR redemption is December only - no exceptions
Leave requests should be submitted via LEAVE_REQUEST sheet only
Manual approval from Pengarah & Timbalan currently updated manually - system tracks status
All data is confidential - keep file secure
Prepared By: Zainal Abidin, Penyelia Unit Rating (RTG)
Date: September 2026
Version: 1.0 - Initial Release
Effective: Januari 2026
For questions or issues, contact Zainal Abidin directly.# pengurusan-cuti
bagi urusan cuti kakitangan val