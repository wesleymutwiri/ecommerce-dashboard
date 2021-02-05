<div class="container">
    <div class="recruitment-header">
        <h3>Recruitment Progress</h3>
        <button class="open">View All</button>
    </div>
    <div class="recruitment-body">
        <table>
            <tr class="row header">
                <th class="initial">Full Name</th>
                <th>Designation</th>
                <th>Status</th>
            </tr>
            <tr class="row">
                <td class="image-description">
                    <img src="https://randomuser.me/api/portraits/men/4.jpg" alt="" class="avatar">
                    Wesley Mochiemo
                </td>
                <td>Project Manager</td>
                <td><span class="status"></span> Tech Interview</td>
            </tr>
            <tr class="row">
                <td class="image-description">
                    <img src="https://randomuser.me/api/portraits/men/4.jpg" alt="" class="avatar">
                    Wesley Mochiemo
                </td>
                <td>Project Manager</td>
                <td><span class="status"></span> Tech Interview</td>
            </tr>
            <tr class="row">
                <td class="image-description">
                    <img src="https://randomuser.me/api/portraits/women/3.jpg" alt="" class="avatar">
                    Wesley Mochiemo
                </td>
                <td>Project Manager</td>
                <td><span class="status"></span> Tech Interview</td>
            </tr>
            <tr class="row">
                <td class="image-description">
                    <img src="https://randomuser.me/api/portraits/men/6.jpg" alt="" class="avatar">
                    Wesley Mochiemo
                </td>
                <td>Project Manager</td>
                <td><span class="status"></span> Tech Interview</td>
            </tr>
            <tr class="row">
                <td class="image-description">
                    <img src="https://randomuser.me/api/portraits/women/4.jpg" alt="" class="avatar">
                    Wesley Mochiemo
                </td>
                <td>Project Manager</td>
                <td><span class="status"></span> Tech Interview</td>
            </tr>
        </table>
    </div>
</div>

<style>
    .container {
        width: 100%;
        max-width: 800px;
        padding: 0px 30px;
        margin-top: 30px;
        background: #fff;
        border-radius: 30px;
    }

    .recruitment-header {
        display: flex;
        justify-content: space-between;
        padding: 20px 10px;
        align-items: center;
        font-size: 1.1rem;
    }

    .open {
        background: #ed960b;
        color: #fff;
        border-radius: 20px;
        padding: 12px 35px;
        cursor: pointer;
        outline: none;
        border: none;
        box-shadow: 0 4px #999;
    }

    .open:active {
        box-shadow: 0 1px #666;
    }

    .recruitment-body {
        overflow-x: auto;
    }

    .recruitment-body table {
        width: 100%;
        text-align: left;
        padding: 0px 10px;
        border-collapse: collapse;
    }

    th {
        padding: 20px 0px;
        font-family: 'Raleway', sans-serif;
        font-weight: lighter;
        color: rgba(0, 0, 0, 0.603);
    }

    .row.header {
        border-top: 0.5px solid rgba(0, 0, 0, 0.116);
        border-bottom: 0.5px solid rgba(0, 0, 0, 0.116);
    }

    td {
        padding: 20px 0px;
    }

    .avatar {
        width: 40px;
        height: 40px;
        border-radius: 50%;
        margin: 0px 10px;
    }

    .image-description {
        display: flex;
        align-items: center;
    }

    .status {
        border-radius: 50%;
        height: 10px;
        width: 10px;
        background: greenyellow;
        display: inline-block;
    }

    .initial {
        padding-left: 10px;
    }
</style>