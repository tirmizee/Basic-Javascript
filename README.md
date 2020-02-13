# Basic-Javascript

    var datas = [
      { id: "1", code: "MFLOWC00001", desc: "รถบรรทุก 4 ล้อ", status: 'ใช้งาน' },
      { id: "2", code: "MFLOWC00002", desc: "รถบรรทุก 6 ล้อ", status: 'ใช้งาน' },
      { id: "3", code: "MFLOWC00003", desc: "รถบรรทุก 10 ล้อ", status: 'ใช้งาน' },
      { id: "4", code: "MFLOWC00004", desc: "รถบรรทุก 20 ล้อ", status: 'ใช้งาน' },
    ];
    var ids = ["1","2"];
    var res = datas.filter((e) => {
      return !ids.includes(e.id);
    });
    document.getElementById("demo").innerHTML = JSON.stringify(res);
