# Portal-SMKS-GBNimport { Jurusan, AgendaItem, FasilitasItem, GaleriItem, FaqItem, PendaftarPPDB, GtkItem, SiswaDapodik } from '../types.ts';

export const PROFIL_SEKOLAH = {
  nama: 'SMKS GIAT BANGUN NEGERI',
  namaPendek: 'SMK Giat Bangun Negeri',
  semboyan: 'Unggul, Berkarakter & Profesional',
  kepalaSekolah: 'ILHAM S, S. IP., Gr.',
  jabatanKepalaSekolah: 'Kepala Sekolah SMKS Giat Bangun Negeri',
  sambutan: `Assalamu'alaikum Warahmatullahi Wabarakatuh...`,
  visi: 'Terwujudnya sekolah kejuruan yang unggul dalam mencetak lulusan profesional, berakhlak mulia, berwawasan global, dan siap kerja.',
  misi: [
    'Menyelenggarakan pendidikan kejuruan berbasis Kurikulum Merdeka yang adaptif terhadap kebutuhan dunia industri.',
    'Mengembangkan karakter peserta didik melalui pembiasaan kedisiplinan, integritas, dan jiwa kepemimpinan.',
    'Meningkatkan kompetensi tenaga pendidik secara berkala dan berkesinambungan.',
    'Menjalin kemitraan yang luas dengan dunia usaha dan dunia industri (DU/DI).'
  ],
  nilaiBudaya: [
    { huruf: 'G', label: 'Gigih', desc: 'Pantang menyerah dalam mengasah keahlian dan mencari solusi' },
    { huruf: 'I', label: 'Integritas', desc: 'Jujur, amanah, dan beretika dalam karya maupun tindakan' },
    { huruf: 'A', label: 'Adaptif', desc: 'Cepat menyesuaikan diri dengan kemajuan teknologi modern' },
    { huruf: 'T', label: 'Terampil', desc: 'Menguasai keterampilan vokasi siap pakai berstandar industri' }
  ],
  npsn: '69982411',
  kodeRegistrasiDapodik: 'GBN-2026-DPK-9921',
  luasLahan: '1,5 Hektare (15.000 m²)',
  status: 'Swasta / Terakreditasi C',
  jamOperasional: 'Senin - Sabtu, 07.15 - 13.11 WIB',
  alamat: 'Jln Pendidikan no. 20 Kelurahan Bambaea (Halaman SMKS Giat Bangun Negeri, Lahan 1,5 Hektare)',
  mapsUrl: 'https://maps.app.goo.gl/YJ4EVTwNsLsXVBJdA',
  email: 'smksgbn@gmail.com',
  telepon: '+62 822-9178-7878',
  whatsapp: '+62 822-9178-7878'
};

// STATISTIK RESMI SEKOLAH
export const STATISTIK_SEKOLAH = {
  pesertaDidik: 18,
  gtk: 10,
  guru: 8,
  tendik: 2,
  rombel: 3,
  lahan: '1,5 Hektare (15.000 m²)',
  npsn: '69982411'
};

// 3 ROMBEL (KELAS X, XI, XII)
export const DAFTAR_ROMBEL = [
  {
    id: 'rombel-x',
    nama: 'Rombel X',
    tingkat: 'Kelas X',
    jumlahSiswa: 1,
    waliKelas: 'Salma Saputri, S.Pd.',
    ruang: 'Ruang Materi'
  },
  {
    id: 'rombel-xi',
    nama: 'Rombel XI ,
    tingkat: 'Kelas XI',
    jumlahSiswa: 4,
    waliKelas: 'Salli Novianti S.Pd.',
    ruang: 'Ruang Materi'
  },
  {
    id: 'rombel-xii',
    nama: 'Rombel XII - ',
    tingkat: 'Kelas XII',
    jumlahSiswa: 13,
    waliKelas: 'Resky Aulia Ramadani S.Pd.',
    ruang: 'Desain Komunikasi Visual'
  }
];

// 10 GTK: 8 GURU + 2 TENDIK
export const DAFTAR_GTK: GtkItem[] = [
  {
    nama: 'ILHAM S, S. IP., Gr.',
    jabatan: 'Kepala Sekolah / Penanggung Jawab Satuan Pendidikan',
    nuptk: ' 1135767668137073',
    status: 'GTY / Guru Tetap Yayasan',
    pendidikan: 'S1 Ilmu Pemerintahan (S. IP., Gr.)',
    sertifikasi: 'Pendidik Profesional (Gr.)',
    kategori: 'Tendik'
  },
  {
    nama: 'Resky Aulia Ramadani S.Pd., Gr.',
    jabatan: 'Wakil Kepala Sekolah Bid. Kurikulum & Guru RPL',
    nuptk: '4461779680230062',
    status: 'GTY',
    pendidikan: 'S1 Bahasa IndonesiA',
    sertifikasi: 'Pendidik Profesional (Gr.)',
    kategori: 'Guru Bahasa Indonesia'
  },
  {
    nama: 'Nurhaema, S.Pd., M.Pd., Gr.',
    jabatan: 'Kepala Sekolah SDS Giat Bangun Negeri',
    nuptk: '198704102011012028',
    status: 'PNS',
    pendidikan: 'S2 Pendidikan Ekonomi',
    sertifikasi: 'Pendidik Profesional (Gr.)',
    kategori: 'Tendik'
  },
  {
    nama: 'Bambang Trianto, S. T., M. Eng.',
    jabatan: 'Kepala Program Keahlian Otomotif (TKRO) & Guru Vokasi',
    nuptk: '9034761653130025',
    status: 'Guru Tetap',
    pendidikan: 'S2 Teknik Mesin Otomotif',
    sertifikasi: 'Asesor Kompetensi BNSP Otomotif',
    kategori: 'Guru'
  },
  {
    nama: 'Maya Indriani, S. E., M. M.',
    jabatan: 'Kepala Program Keahlian Perkantoran (MPLB) & Guru Bisnis',
    nuptk: '5621748650200041',
    status: 'Guru Tetap',
    pendidikan: 'S2 Magister Manajemen',
    sertifikasi: 'Asesor BNSP Administrasi Perkantoran',
    kategori: 'Guru'
  },
  {
    nama: 'Ahmad Fauzi, S. T.',
    jabatan: 'Guru Teknik Jaringan Komputer & Telekomunikasi (TKJ)',
    nuptk: '6712759654120019',
    status: 'Guru Tetap',
    pendidikan: 'S1 Teknik Elektro / Jaringan',
    sertifikasi: 'Sertifikasi Mikrotik MTCNA / Pendidik',
    kategori: 'Guru'
  },
  {
    nama: 'Ridwan Kamiludin, S. Pd.',
    jabatan: 'Guru Matematika Terapan & Koordinator Projek P5',
    nuptk: '8923762656110048',
    status: 'Guru Tetap',
    pendidikan: 'S1 Pendidikan Matematika',
    sertifikasi: 'Pendidik Profesional',
    kategori: 'Guru'
  },
  {
    nama: 'Siti Rahmawati, S. Pd.',
    jabatan: 'Guru Bahasa Inggris Kejuruan & Literasi Digital',
    nuptk: '4129758655200037',
    status: 'Guru Tetap',
    pendidikan: 'S1 Pendidikan Bahasa Inggris',
    sertifikasi: 'Pendidik Profesional',
    kategori: 'Guru'
  },
  // 2 Tendik (Tenaga Kependidikan)
  {
    nama: 'Fahmi Nugraha, S. Kom.',
    jabatan: 'Tenaga Kependidikan 1: Operator Utama Dapodik & IT Admin',
    nuptk: '1249763655110052',
    status: 'Tenaga Kependidikan Tetap',
    pendidikan: 'S1 Teknik Informatika',
    sertifikasi: 'Sertifikasi Tenaga Administrasi Sekolah (TAS)',
    kategori: 'Tendik'
  },
  {
    nama: 'Rina Agustina, A. Md.',
    jabatan: 'Tenaga Kependidikan 2: Kepala Tata Usaha, Keuangan & Persuratan',
    nuptk: '2350764656220063',
    status: 'Tenaga Kependidikan Tetap',
    pendidikan: 'D3 Administrasi Perkantoran & Keuangan',
    sertifikasi: 'Sertifikasi Pengelolaan Administrasi & BOS',
    kategori: 'Tendik'
  }
];

// 18 SISWA TERSEBAR MERATA DI 3 ROMBEL
export const DAFTAR_SISWA_18: SiswaDapodik[] = [
  // 6 Siswa di Rombel X
  { id: 'PD-01', nisn: '0089234812', nik: '3201021203080001', nama: 'Ahmad Rizky Pratama', rombel: 'Rombel X - Vokasi Industri', tingkat: 'Kelas X', jurusan: 'RPL & AI', jenisKelamin: 'L' },
  { id: 'PD-02', nisn: '0087452391', nik: '3201025508080002', nama: 'Siti Nur Aisyah', rombel: 'Rombel X - Vokasi Industri', tingkat: 'Kelas X', jurusan: 'MPLB', jenisKelamin: 'P' },
  { id: 'PD-03', nisn: '0081239845', nik: '3201021405080003', nama: 'Bayu Saputra', rombel: 'Rombel X - Vokasi Industri', tingkat: 'Kelas X', jurusan: 'TKRO', jenisKelamin: 'L' },
  { id: 'PD-04', nisn: '0086541289', nik: '3201024809080004', nama: 'Dinda Ayu Maharani', rombel: 'Rombel X - Vokasi Industri', tingkat: 'Kelas X', jurusan: 'TKJ', jenisKelamin: 'P' },
  { id: 'PD-05', nisn: '0083214567', nik: '3201021901080005', nama: 'Fajar Maulana', rombel: 'Rombel X - Vokasi Industri', tingkat: 'Kelas X', jurusan: 'RPL & AI', jenisKelamin: 'L' },
  { id: 'PD-06', nisn: '0089876543', nik: '3201026211080006', nama: 'Gita Permatasari', rombel: 'Rombel X - Vokasi Industri', tingkat: 'Kelas X', jurusan: 'MPLB', jenisKelamin: 'P' },

  // 6 Siswa di Rombel XI
  { id: 'PD-07', nisn: '0071234567', nik: '3201021102070007', nama: 'Ilham Ramadhan', rombel: 'Rombel XI - Vokasi Terapan & PKL', tingkat: 'Kelas XI', jurusan: 'TKJ', jenisKelamin: 'L' },
  { id: 'PD-08', nisn: '0072345678', nik: '3201024406070008', nama: 'Intan Nurhaliza', rombel: 'Rombel XI - Vokasi Terapan & PKL', tingkat: 'Kelas XI', jurusan: 'MPLB', jenisKelamin: 'P' },
  { id: 'PD-09', nisn: '0073456789', nik: '3201021509070009', nama: 'Kevin Aditya Pratama', rombel: 'Rombel XI - Vokasi Terapan & PKL', tingkat: 'Kelas XI', jurusan: 'TKRO', jenisKelamin: 'L' },
  { id: 'PD-10', nisn: '0074567890', nik: '3201025212070010', nama: 'Larasati Putri', rombel: 'Rombel XI - Vokasi Terapan & PKL', tingkat: 'Kelas XI', jurusan: 'RPL & AI', jenisKelamin: 'P' },
  { id: 'PD-11', nisn: '0075678901', nik: '3201021804070011', nama: 'Muhammad Danang', rombel: 'Rombel XI - Vokasi Terapan & PKL', tingkat: 'Kelas XI', jurusan: 'TKRO', jenisKelamin: 'L' },
  { id: 'PD-12', nisn: '0076789012', nik: '3201026507070012', nama: 'Nabila Zahra', rombel: 'Rombel XI - Vokasi Terapan & PKL', tingkat: 'Kelas XI', jurusan: 'TKJ', jenisKelamin: 'P' },

  // 6 Siswa di Rombel XII
  { id: 'PD-13', nisn: '0061234567', nik: '3201021001060013', nama: 'Oki Setiawan', rombel: 'Rombel XII - Uji Kompetensi BNSP', tingkat: 'Kelas XII', jurusan: 'RPL & AI', jenisKelamin: 'L' },
  { id: 'PD-14', nisn: '0062345678', nik: '3201024305060014', nama: 'Putri Handayani', rombel: 'Rombel XII - Uji Kompetensi BNSP', tingkat: 'Kelas XII', jurusan: 'MPLB', jenisKelamin: 'P' },
  { id: 'PD-15', nisn: '0063456789', nik: '3201021608060015', nama: 'Rendy Kurniawan', rombel: 'Rombel XII - Uji Kompetensi BNSP', tingkat: 'Kelas XII', jurusan: 'TKRO', jenisKelamin: 'L' },
  { id: 'PD-16', nisn: '0064567890', nik: '3201025810060016', nama: 'Siska Amelia', rombel: 'Rombel XII - Uji Kompetensi BNSP', tingkat: 'Kelas XII', jurusan: 'TKJ', jenisKelamin: 'P' },
  { id: 'PD-17', nisn: '0065678901', nik: '3201022103060017', nama: 'Teguh Prakoso', rombel: 'Rombel XII - Uji Kompetensi BNSP', tingkat: 'Kelas XII', jurusan: 'RPL & AI', jenisKelamin: 'L' },
  { id: 'PD-18', nisn: '0066789012', nik: '3201026312060018', nama: 'Vina Oktavia', rombel: 'Rombel XII - Uji Kompetensi BNSP', tingkat: 'Kelas XII', jurusan: 'MPLB', jenisKelamin: 'P' }

import React, { useState, useEffect } from 'react';
import { 
  X, CheckCircle2, Users, GraduationCap, 
  Printer, Save, Search, Check, FileSpreadsheet, ShieldCheck, UserCheck 
} from 'lucide-react';
import { PROFIL_SEKOLAH, DAFTAR_GTK, DAFTAR_SISWA_18, DAFTAR_ROMBEL } from '../data/schoolData.ts';

interface PresensiModalProps {
  isOpen: boolean;
  onClose: () => void;
}

type PresensiStatus = 'Hadir' | 'Izin' | 'Sakit' | 'Alpa';

interface KehadiranRecord {
  status: PresensiStatus;
  waktu: string;
  keterangan?: string;
}

export const PresensiModal: React.FC<PresensiModalProps> = ({ isOpen, onClose }) => {
  const [activeTab, setActiveTab] = useState<'gtk' | 'siswa'>('gtk');
  const [selectedRombel, setSelectedRombel] = useState<string>('semua');
  const [searchQuery, setSearchQuery] = useState('');
  const [currentTime, setCurrentTime] = useState<string>('');
  const [currentDate, setCurrentDate] = useState<string>('');
  const [saveToast, setSaveToast] = useState<string | null>(null);

  // Initial State GTK (10 Orang: 8 Guru, 2 Tendik)
  const [presensiGtk, setPresensiGtk] = useState<Record<string, KehadiranRecord>>(() => {
    const saved = localStorage.getItem('smks_gbn_presensi_gtk_v1');
    if (saved) {
      try { return JSON.parse(saved); } catch (e) { /* ignore */ }
    }
    const initial: Record<string, KehadiranRecord> = {};
    DAFTAR_GTK.forEach((g) => {
      initial[g.nuptk] = { status: 'Hadir', waktu: '07.05 WIB' };
    });
    return initial;
  });

  // Initial State Siswa (18 Siswa di 3 Rombel)
  const [presensiSiswa, setPresensiSiswa] = useState<Record<string, KehadiranRecord>>(() => {
    const saved = localStorage.getItem('smks_gbn_presensi_siswa_v1');
    if (saved) {
      try { return JSON.parse(saved); } catch (e) { /* ignore */ }
    }
    const initial: Record<string, KehadiranRecord> = {};
    DAFTAR_SISWA_18.forEach((s) => {
      initial[s.id] = { status: 'Hadir', waktu: '07.10 WIB' };
    });
    return initial;
  });

  useEffect(() => {
    const updateTime = () => {
      const now = new Date();
      setCurrentTime(now.toLocaleTimeString('id-ID', { hour: '2-digit', minute: '2-digit', second: '2-digit' }) + ' WIB');
      setCurrentDate(now.toLocaleDateString('id-ID', { weekday: 'long', day: 'numeric', month: 'long', year: 'numeric' }));
    };
    updateTime();
    const interval = setInterval(updateTime, 1000);
    return () => clearInterval(interval);
  }, []);

  if (!isOpen) return null;

  const handleUpdateGtk = (nuptk: string, status: PresensiStatus) => {
    setPresensiGtk(prev => ({
      ...prev,
      [nuptk]: { status, waktu: status === 'Hadir' ? (prev[nuptk]?.waktu || '07.12 WIB') : '-' }
    }));
  };

  const handleUpdateSiswa = (id: string, status: PresensiStatus) => {
    setPresensiSiswa(prev => ({
      ...prev,
      [id]: { status, waktu: status === 'Hadir' ? (prev[id]?.waktu || '07.15 WIB') : '-' }
    }));
  };

  const handleSetAllGtkHadir = () => {
    const updated: Record<string, KehadiranRecord> = {};
    DAFTAR_GTK.forEach((g) => {
      updated[g.nuptk] = { status: 'Hadir', waktu: '07.10 WIB' };
    });
    setPresensiGtk(updated);
    showToast('Seluruh 10 GTK (8 Guru & 2 Tendik) ditandai Hadir!');
  };

  const handleSetAllSiswaHadir = () => {
    const updated = { ...presensiSiswa };
    const targetStudents = selectedRombel === 'semua' 
      ? DAFTAR_SISWA_18 
      : DAFTAR_SISWA_18.filter(s => s.rombel === selectedRombel);
    
    targetStudents.forEach(s => {
      updated[s.id] = { status: 'Hadir', waktu: '07.12 WIB' };
    });
    setPresensiSiswa(updated);
    showToast(`Seluruh siswa (${targetStudents.length} siswa) ditandai Hadir!`);
  };

  const handleSavePresensi = () => {
    localStorage.setItem('smks_gbn_presensi_gtk_v1', JSON.stringify(presensiGtk));
    localStorage.setItem('smks_gbn_presensi_siswa_v1', JSON.stringify(presensiSiswa));
    showToast('Presensi berhasil disimpan ke basis data lokal sekolah!');
  };

  const showToast = (msg: string) => {
    setSaveToast(msg);
    setTimeout(() => setSaveToast(null), 3500);
  };

  const handleExportCsv = () => {
    let csvContent = 'data:text/csv;charset=utf-8,';
    csvContent += `REKAPITULASI PRESENSI HARIAN SMKS GIAT BANGUN NEGERI\n`;
    csvContent += `Tanggal,${currentDate}\nNPSN,${PROFIL_SEKOLAH.npsn}\nKepala Sekolah,${PROFIL_SEKOLAH.kepalaSekolah}\n\n`;

    csvContent += `--- DATA PRESENSI GTK (10 ORANG: 8 GURU & 2 TENDIK) ---\n`;
    csvContent += `No,Nama,Kategori,Jabatan,NUPTK,Status,Jam Masuk\n`;
    DAFTAR_GTK.forEach((g, idx) => {
      const rec = presensiGtk[g.nuptk] || { status: 'Hadir', waktu: '07.05 WIB' };
      csvContent += `${idx + 1},"${g.nama}",${g.kategori},"${g.jabatan}",${g.nuptk},${rec.status},${rec.waktu}\n`;
    });

    csvContent += `\n--- DATA PRESENSI PESERTA DIDIK (18 SISWA - 3 ROMBEL) ---\n`;
    csvContent += `No,Nama Siswa,NISN,Rombel,Tingkat,Jurusan,JK,Status,Jam Masuk\n`;
    DAFTAR_SISWA_18.forEach((s, idx) => {
      const rec = presensiSiswa[s.id] || { status: 'Hadir', waktu: '07.10 WIB' };
      csvContent += `${idx + 1},"${s.nama}",${s.nisn},"${s.rombel}",${s.tingkat},${s.jurusan},${s.jenisKelamin},${rec.status},${rec.waktu}\n`;
    });

    const link = document.createElement('a');
    link.setAttribute('href', encodeURI(csvContent));
    link.setAttribute('download', `Presensi_SMKS_GBN_${new Date().toISOString().slice(0, 10)}.csv`);
    document.body.appendChild(link);
    link.click();
    document.body.removeChild(link);
    showToast('File CSV Rekap Presensi berhasil diunduh!');
  };

  const gtkHadirCount = DAFTAR_GTK.filter(g => (presensiGtk[g.nuptk]?.status || 'Hadir') === 'Hadir').length;
  const siswaHadirCount = DAFTAR_SISWA_18.filter(s => (presensiSiswa[s.id]?.status || 'Hadir') === 'Hadir').length;

  const filteredGtk = DAFTAR_GTK.filter(g => 
    g.nama.toLowerCase().includes(searchQuery.toLowerCase()) ||
    g.jabatan.toLowerCase().includes(searchQuery.toLowerCase()) ||
    g.nuptk.includes(searchQuery)
  );

  const filteredSiswa = DAFTAR_SISWA_18.filter(s => {
    const matchRombel = selectedRombel === 'semua' || s.rombel === selectedRombel;
    const matchQuery = s.nama.toLowerCase().includes(searchQuery.toLowerCase()) ||
                       s.nisn.includes(searchQuery) ||
                       s.jurusan.toLowerCase().includes(searchQuery.toLowerCase());
    return matchRombel && matchQuery;
  });

  return (
    <div className="fixed inset-0 z-50 flex items-center justify-center p-2 sm:p-4 bg-slate-950/80 backdrop-blur-md">
      <div className="bg-slate-900 border border-slate-700 w-full max-w-5xl rounded-3xl shadow-2xl flex flex-col max-h-[92vh] overflow-hidden">
        {/* Header */}
        <div className="bg-gradient-to-r from-blue-900 via-blue-950 to-slate-900 px-6 py-5 border-b border-blue-800 flex items-center justify-between text-white shrink-0">
          <div className="flex items-center space-x-3.5">
            <div className="w-11 h-11 rounded-2xl bg-amber-400 text-slate-900 flex items-center justify-center shadow font-black">
              <UserCheck className="w-6 h-6" />
            </div>
            <div>
              <div className="flex items-center space-x-2">
                <h3 className="text-lg sm:text-xl font-black">Sistem Presensi Harian Digital</h3>
                <span className="hidden sm:inline-block px-2.5 py-0.5 rounded-full text-[11px] font-bold bg-emerald-500/20 text-emerald-300 border border-emerald-500/30">
                  Aktif • TA 2026/2027
                </span>
              </div>
              <p className="text-xs text-blue-200">
                SMKS Giat Bangun Negeri • NPSN: {PROFIL_SEKOLAH.npsn} • Lahan 1,5 Hektare
              </p>
            </div>
          </div>
          <div className="flex items-center space-x-3">
            <div className="hidden md:flex flex-col text-right font-mono text-xs">
              <span className="text-amber-400 font-bold">{currentTime}</span>
              <span className="text-slate-300 text-[11px]">{currentDate}</span>
            </div>
            <button onClick={onClose} className="p-2 rounded-xl text-slate-400 hover:text-white hover:bg-slate-800 transition">
              <X className="w-6 h-6" />
            </button>
          </div>
        </div>

        {/* Status Ringkas */}
        <div className="bg-slate-950/90 px-6 py-3 border-b border-slate-800 grid grid-cols-2 sm:grid-cols-4 gap-3 text-xs shrink-0">
          <div className="bg-slate-900/80 p-2.5 rounded-xl border border-slate-800 flex items-center justify-between">
            <div>
              <span className="text-slate-400 text-[10px] uppercase font-bold block">Peserta Didik</span>
              <span className="text-white font-bold text-sm">18 Siswa</span>
            </div>
            <span className="text-[10px] text-emerald-400 font-semibold bg-emerald-500/10 px-2 py-0.5 rounded">3 Rombel</span>
          </div>
          <div className="bg-slate-900/80 p-2.5 rounded-xl border border-slate-800 flex items-center justify-between">
            <div>
              <span className="text-slate-400 text-[10px] uppercase font-bold block">Pendidik & Tendik (GTK)</span>
              <span className="text-white font-bold text-sm">10 Orang</span>
            </div>
            <span className="text-[10px] text-blue-300 font-semibold bg-blue-500/10 px-2 py-0.5 rounded">8 Guru • 2 Tendik</span>
          </div>
          <div className="bg-slate-900/80 p-2.5 rounded-xl border border-slate-800 flex items-center justify-between">
            <div>
              <span className="text-slate-400 text-[10px] uppercase font-bold block">Kehadiran Siswa</span>
              <span className="text-amber-400 font-bold text-sm">{siswaHadirCount} / 18</span>
            </div>
          </div>
          <div className="bg-slate-900/80 p-2.5 rounded-xl border border-slate-800 flex items-center justify-between">
            <div>
              <span className="text-slate-400 text-[10px] uppercase font-bold block">Kehadiran GTK</span>
              <span className="text-emerald-400 font-bold text-sm">{gtkHadirCount} / 10</span>
            </div>
          </div>
        </div>

        {/* Tab & Filter Controls */}
        <div className="px-6 py-4 bg-slate-900/90 border-b border-slate-800 flex flex-col md:flex-row items-stretch md:items-center justify-between gap-3 shrink-0">
          <div className="flex bg-slate-950 p-1 rounded-xl border border-slate-800">
            <button
              onClick={() => setActiveTab('gtk')}
              className={`px-4 py-2 rounded-lg text-xs font-bold transition flex items-center space-x-2 cursor-pointer ${
                activeTab === 'gtk' ? 'bg-blue-600 text-white shadow' : 'text-slate-400 hover:text-white'
              }`}
            >
              <GraduationCap className="w-4 h-4 text-amber-400" />
              <span>Presensi GTK (10 Orang: 8 Guru, 2 Tendik)</span>
            </button>
            <button
              onClick={() => setActiveTab('siswa')}
              className={`px-4 py-2 rounded-lg text-xs font-bold transition flex items-center space-x-2 cursor-pointer ${
                activeTab === 'siswa' ? 'bg-blue-600 text-white shadow' : 'text-slate-400 hover:text-white'
              }`}
            >
              <Users className="w-4 h-4 text-emerald-400" />
              <span>Presensi Peserta Didik (18 Siswa - 3 Rombel)</span>
            </button>
          </div>

          <div className="flex items-center space-x-2">
            <div className="relative flex-1 md:w-60">
              <Search className="w-4 h-4 text-slate-500 absolute left-3 top-2.5" />
              <input
                type="text"
                placeholder={activeTab === 'gtk' ? 'Cari nama guru / tendik...' : 'Cari nama siswa / NISN...'}
                value={searchQuery}
                onChange={(e) => setSearchQuery(e.target.value)}
                className="w-full bg-slate-950 border border-slate-800 rounded-xl pl-9 pr-3 py-1.5 text-xs text-white focus:outline-none focus:border-blue-500"
              />
            </div>
            <button
              onClick={activeTab === 'gtk' ? handleSetAllGtkHadir : handleSetAllSiswaHadir}
              className="bg-emerald-600 hover:bg-emerald-500 text-white font-bold text-xs px-3 py-2 rounded-xl transition flex items-center space-x-1 shrink-0 shadow cursor-pointer"
            >
              <Check className="w-3.5 h-3.5" />
              <span>Semua Hadir</span>
            </button>
          </div>
        </div>

        {/* Filter Rombel Siswa */}
        {activeTab === 'siswa' && (
          <div className="px-6 py-2.5 bg-slate-950/70 border-b border-slate-800/80 flex flex-wrap items-center gap-2 text-xs shrink-0">
            <span className="text-slate-400 font-bold mr-1">Filter Rombel:</span>
            <button
              onClick={() => setSelectedRombel('semua')}
              className={`px-3 py-1 rounded-lg text-xs font-semibold transition cursor-pointer ${
                selectedRombel === 'semua' ? 'bg-blue-600 text-white' : 'bg-slate-900 text-slate-400 hover:text-white border border-slate-800'
              }`}
            >
              Semua (18 Siswa)
            </button>
            {DAFTAR_ROMBEL.map((rombel) => (
              <button
                key={rombel.id}
                onClick={() => setSelectedRombel(rombel.nama)}
                className={`px-3 py-1 rounded-lg text-xs font-semibold transition cursor-pointer flex items-center space-x-1.5 ${
                  selectedRombel === rombel.nama ? 'bg-blue-600 text-white shadow' : 'bg-slate-900 text-slate-400 hover:text-white border border-slate-800'
                }`}
              >
                <span>{rombel.nama}</span>
                <span className="px-1.5 py-0.2 bg-black/40 rounded text-[10px] text-amber-300">{rombel.jumlahSiswa} Siswa</span>
              </button>
            ))}
          </div>
        )}

        {/* Tabel Data Presensi */}
        <div className="p-6 overflow-y-auto flex-1 space-y-4">
          {activeTab === 'gtk' ? (
            <div className="overflow-x-auto rounded-2xl border border-slate-800">
              <table className="w-full text-left text-xs">
                <thead className="bg-slate-950 text-slate-400 uppercase font-bold border-b border-slate-800">
                  <tr>
                    <th className="py-3 px-4">No</th>
                    <th className="py-3 px-4">Nama GTK</th>
                    <th className="py-3 px-4">Kategori & Jabatan</th>
                    <th className="py-3 px-4">NUPTK</th>
                    <th className="py-3 px-4 text-center">Status Presensi</th>
                    <th className="py-3 px-4 text-right">Jam Masuk</th>
                  </tr>
                </thead>
                <tbody className="divide-y divide-slate-800/80 text-slate-200">
                  {filteredGtk.map((gtk, idx) => {
                    const rec = presensiGtk[gtk.nuptk] || { status: 'Hadir', waktu: '07.05 WIB' };
                    const isTendik = gtk.kategori === 'Tendik';
                    return (
                      <tr key={gtk.nuptk} className="hover:bg-slate-800/50 transition">
                        <td className="py-3.5 px-4 font-mono text-slate-500">{idx + 1}</td>
                        <td className="py-3.5 px-4 font-bold text-white text-sm">{gtk.nama}</td>
                        <td className="py-3.5 px-4">
                          <span className={`px-2 py-0.5 rounded text-[10px] font-bold ${
                            isTendik ? 'bg-purple-500/20 text-purple-300 border border-purple-500/30' : 'bg-blue-500/20 text-blue-300 border border-blue-500/30'
                          }`}>
                            {isTendik ? 'Tendik (2)' : 'Guru (8)'}
                          </span>
                          <p className="text-xs text-slate-300 mt-0.5">{gtk.jabatan}</p>
                        </td>
                        <td className="py-3.5 px-4 font-mono text-slate-400 text-xs">{gtk.nuptk}</td>
                        <td className="py-3.5 px-4">
                          <div className="flex items-center justify-center space-x-1 bg-slate-950 p-1 rounded-xl border border-slate-800">
                            {(['Hadir', 'Izin', 'Sakit', 'Alpa'] as PresensiStatus[]).map((st) => (
                              <button
                                key={st}
                                onClick={() => handleUpdateGtk(gtk.nuptk, st)}
                                className={`px-2.5 py-1 rounded-lg text-xs font-bold transition cursor-pointer ${
                                  rec.status === st
                                    ? st === 'Hadir' ? 'bg-emerald-600 text-white shadow'
                                      : st === 'Izin' ? 'bg-amber-500 text-slate-900 shadow'
                                      : st === 'Sakit' ? 'bg-blue-500 text-white shadow'
                                      : 'bg-rose-600 text-white shadow'
                                    : 'text-slate-400 hover:text-white'
                                }`}
                              >
                                {st}
                              </button>
                            ))}
                          </div>
                        </td>
                        <td className="py-3.5 px-4 text-right font-mono text-slate-300 font-bold">{rec.waktu}</td>
                      </tr>
                    );
                  })}
                </tbody>
              </table>
            </div>
          ) : (
            <div className="overflow-x-auto rounded-2xl border border-slate-800">
              <table className="w-full text-left text-xs">
                <thead className="bg-slate-950 text-slate-400 uppercase font-bold border-b border-slate-800">
                  <tr>
                    <th className="py-3 px-4">No</th>
                    <th className="py-3 px-4">Nama Siswa</th>
                    <th className="py-3 px-4">NISN</th>
                    <th className="py-3 px-4">Rombel</th>
                    <th className="py-3 px-4">Jurusan</th>
                    <th className="py-3 px-4 text-center">Status Presensi</th>
                    <th className="py-3 px-4 text-right">Jam Masuk</th>
                  </tr>
                </thead>
                <tbody className="divide-y divide-slate-800/80 text-slate-200">
                  {filteredSiswa.map((siswa, idx) => {
                    const rec = presensiSiswa[siswa.id] || { status: 'Hadir', waktu: '07.10 WIB' };
                    return (
                      <tr key={siswa.id} className="hover:bg-slate-800/50 transition">
                        <td className="py-3.5 px-4 font-mono text-slate-500">{idx + 1}</td>
                        <td className="py-3.5 px-4 font-bold text-white text-sm">{siswa.nama}</td>
                        <td className="py-3.5 px-4 font-mono text-amber-400 font-semibold">{siswa.nisn}</td>
                        <td className="py-3.5 px-4">
                          <span className="px-2 py-0.5 rounded text-[10px] font-bold bg-slate-800 text-blue-300 border border-slate-700">
                            {siswa.rombel}
                          </span>
                        </td>
                        <td className="py-3.5 px-4">
                          <span className="px-2 py-0.5 rounded text-[10px] font-bold bg-amber-400/20 text-amber-300">
                            {siswa.jurusan}
                          </span>
                        </td>
                        <td className="py-3.5 px-4">
                          <div className="flex items-center justify-center space-x-1 bg-slate-950 p-1 rounded-xl border border-slate-800">
                            {(['Hadir', 'Izin', 'Sakit', 'Alpa'] as PresensiStatus[]).map((st) => (
                              <button
                                key={st}
                                onClick={() => handleUpdateSiswa(siswa.id, st)}
                                className={`px-2.5 py-1 rounded-lg text-xs font-bold transition cursor-pointer ${
                                  rec.status === st
                                    ? st === 'Hadir' ? 'bg-emerald-600 text-white shadow'
                                      : st === 'Izin' ? 'bg-amber-500 text-slate-900 shadow'
                                      : st === 'Sakit' ? 'bg-blue-500 text-white shadow'
                                      : 'bg-rose-600 text-white shadow'
                                    : 'text-slate-400 hover:text-white'
                                }`}
                              >
                                {st}
                              </button>
                            ))}
                          </div>
                        </td>
                        <td className="py-3.5 px-4 text-right font-mono text-slate-300 font-bold">{rec.waktu}</td>
                      </tr>
                    );
                  })}
                </tbody>
              </table>
            </div>
          )}
        </div>

        {/* Footer Tombol Aksi */}
        <div className="px-6 py-4 bg-slate-950 border-t border-slate-800 flex flex-col sm:flex-row items-center justify-between gap-3 shrink-0">
          <div className="flex items-center space-x-2 text-xs text-slate-400">
            <ShieldCheck className="w-4 h-4 text-emerald-400" />
            <span>Presensi tervalidasi Kepala Sekolah <strong>{PROFIL_SEKOLAH.kepalaSekolah}</strong></span>
          </div>
          <div className="flex items-center space-x-2.5 w-full sm:w-auto">
            <button
              onClick={handleExportCsv}
              className="flex-1 sm:flex-none bg-slate-800 hover:bg-slate-700 text-white font-bold text-xs px-4 py-2.5 rounded-xl transition flex items-center justify-center space-x-1.5 border border-slate-700 cursor-pointer"
            >
              <FileSpreadsheet className="w-4 h-4 text-emerald-400" />
              <span>Ekspor CSV</span>
            </button>
            <button
              onClick={() => window.print()}
              className="flex-1 sm:flex-none bg-slate-800 hover:bg-slate-700 text-white font-bold text-xs px-4 py-2.5 rounded-xl transition flex items-center justify-center space-x-1.5 border border-slate-700 cursor-pointer"
            >
              <Printer className="w-4 h-4 text-amber-400" />
              <span>Cetak</span>
            </button>
            <button
              onClick={handleSavePresensi}
              className="flex-1 sm:flex-none bg-gradient-to-r from-blue-600 to-blue-700 hover:from-blue-500 hover:to-blue-600 text-white font-bold text-xs px-5 py-2.5 rounded-xl transition shadow-lg flex items-center justify-center space-x-1.5 cursor-pointer"
            >
              <Save className="w-4 h-4 text-amber-300" />
              <span>Simpan Presensi</span>
            </button>
          </div>
        </div>
      </div>
    </div>
  );
};
];
